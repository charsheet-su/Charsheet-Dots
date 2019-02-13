# Charsheet-Dots

This is a font to create dots and checkboxes, designed for character sheet generator http://charsheet.su. It is based on Percolator-expert font and has simple "O" as empty dot and filled "O" as filled dot.

This font also has checkbox character from [Font-Awesome font](https://github.com/FortAwesome/Font-Awesome) and custom filled checkbox.

It looks like this:

![Font sample](https://raw.githubusercontent.com/jehy/Storyteller-Dots/master/font-sample.png)

Add this font to your CSS via the following code:

```css
@font-face {
    font-family: "Dots";
    src: url(../fonts/dots.otf);
}
```
To display empty dot, you should use the following CSS:
```css
.dot-empty
{
    font-family: Dots;
    content: "A";
}

.dot-filled
{
    font-family: Dots;
    content: "B";
}
```
to display checkbox, you should use 
```css
.checkbox-empty
{
    font-family: Dots;
    content: "C";
}

.checkbox-filled
{
    font-family: Dots;
    content: "D";
}
```
Custom characters are made with [FontForge](http://fontforge.github.io/en-US/) application.

You can create your own web applications with storyteller dots
using [JQuery Bar Rating plugin](https://github.com/antennaio/jquery-bar-rating) - you can use theme from `dots.css` for it,
it can also be added via simple import:

```js
import 'charsheet-dots';
```

Your comments and new characters are welcome :)
