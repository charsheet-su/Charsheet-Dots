# Storyteller-Dots
Here is a font to create storyteller dots. It is based on Percolator-expert font and has simple "O" as empty dot and filled "O" as filled dot.

Also is has checkbox character from Font-Awesome font (https://github.com/FortAwesome/Font-Awesome) and custom filled checkbox.
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
Custom characters are made with FontForge (http://fontforge.github.io/en-US/) application
