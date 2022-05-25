# CSS notes and links
>
> Cascading Style Sheets (CSS) are used to style how the HTML (and other languages such as XML and SVG (SVG = Scalable Vector Graphics)) elements are displayed on web pages.
>
> Various web browsers use default styles and there may be some variation between browsers in the appearance of what is displayed. In order to produce consistent styles the programmer can use CSS to impose the styles they prefer.
>
> External style is referenced in a file dedicated to only CSS declarations and no HTML code. The file must end with .css extension. This file is linked in the HTML file, in the HEAD section using the LINK element. These styles will then be used in all subsequent pages unless superceeded by later style declarations.
>
> Internal to a particular page you can use the STYLE element, also placed in the HEAD section.
>
> Since both these methods are placed in the HEAD section, the last read instance will take presidence over the earlier one (properties "Cascade" one over previous).
>
> the third (and highest priority) are styles explisitly declared along with elements in the BODY of an HTML page.
>
> Color is a major part of styling pages and deserves a little more attention. While some basic colors are set by text values such as "RED" or "BLUE", to give the programmer more parameterized control of the complete color pallet, there are 3 basic formats that may be used, Hexidecimal, RGB (Red, Green, Blue), and HSL (Hue, Saturation, Lightness). All three also have a version that allows a 4th parameter to be defined called opacity (4 digit HEX, RGBA and HSLA).
>
> For more, see the links below.
>
> [CSS reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
>
> [Color information](https://blog.bitsrc.io/hex-vs-rgb-vs-hsl-what-is-the-best-method-to-set-css-color-property-f45d2debeee)
>
