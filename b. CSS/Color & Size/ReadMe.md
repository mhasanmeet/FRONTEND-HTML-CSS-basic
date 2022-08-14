## Size Units

CSS Unit are determines the size of a property of an element or its content

1. **Absolute Units**: Units that are "absolute" are the same size regardless of the parent element or window size.

| Absolute Units | Name | Equivalent to|
|-|-|-|
|cm| Centimeters |1cm = 96px/2.54|
|mm|Millimeters|1mm = 1/10th of 1cm|
|Q|Quarter-millimeters|1Q = 1/40th of 1cm|
|in|Inches|1in = 2.54cm = 96px|
|pc|Picas|1pc = 1/6th of 1in|
|pt|Points|1pt = 1/72th of 1in|
|px|Pixels|1px = 1/96th of 1in|

2. **Relative Units**: Relative units are useful for styling responsive sites because they scale relative to the parent or window size (depending upon the unit)

| Relative units | Description |
|-|-|
|%|Relative to the parent element|
|em|Relative to the font size of the element|
|rem|Relative to the font size of the root element|
|ch|Relative to the width of the "0" (zero)|
|vh|Relative to 1% of the viewport's height|
|vmin|Relative to 1% of viewport's smaller dimension|
|vmax|Relative to 1% of viewport's larger dimension|

3. **Viewport-relative units**

| Units | Relative to |
|-|-|
|vw| viewport's width |
|vh| Viewport's height |

4. **Angle units**

Example of Angle units 

```
div{
    transform: rotate(60deg);
}
```
> CSS font's size issue solved by [Joshw Comeau](https://www.joshwcomeau.com/css/surprising-truth-about-pixels-and-accessibility/) 

### What is root font size? 

> The root font size is 16px. It is default font size. 

* Equal pixel value to Ram value

|Pixel Value (PX)|Rem Value|
|-|-|
|14px| 0.875rem|
|15px| 0.9375rem|
|16px| 1rem|
|17px| 1.0625rem|
|18px| 1.125rem|
|19px| 1.1875rem|
|20px| 1.25rem|
|21px| 1.3125rem|

* set in css variable for font

```css

html {
  --14px: 0.875rem;
  --15px: 0.9375rem;
  --16px: 1rem;
  --17px: 1.0625rem;
  --18px: 1.125rem;
  --19px: 1.1875rem;
  --20px: 1.25rem;
  --21px: 1.3125rem;
}

```

or

```css

html {
  --font-size-xs: 0.75rem;
  --font-size-sm: 0.875rem;
  --font-size-md: 1rem;
  --font-size-lg: 1.125rem;
  --font-size-xl: 1.3125rem;
  --font-size-2xl: 1.5rem;
  --font-size-3xl: 2.652rem;
  --font-size-4xl: 4rem;
}

```

## Color Units

* HSL
* HEX
* RGB & RGBA

> ❓ Which color is easy to maintainable? 

> 🔆 The experts says hsl color is easy to maintainable.

### HSL color

hsl(hue, saturation, lightness)

* **hue** =  is a degree of a color wheel from 0 to 360 degree. But we write give value we can omit the degree name. 
* **saturation** = Saturation is a percentage value, 0% means a shade of gray, and 100% is the full color.
* **Lightness** = Lightness is also a percentage, 0% is black, 50% is neither light or dark, 100% is white

Use of hsl color

```css

  filter: saturate(0) brightness(0.3);
  color: hsl(285deg 65% 22%);
  color: hsl(285, 65%, 22%);
  color: hsl(.25turn 50% 50%);

```
### HEX color
### RGB color & RGBA

- rgb (red, green, blue)

* red = 0 to 255 number range or 0% to 100%
* green = 0 to 255 number range or 0% to 100%
* blue = 0 to 255 number range or 0% to 100%

> When use percentage use % sign in all value even it is 0. without % sign the value will not give the correct result. 

```css

  color: rgb(0 255 0); // green color number range
  color: rgb(0% 100% 0%); // green color percentage range
  color: rgb(0 100% 0); //This will not work
  color: rgb(0, 255, -110, .5); //Negative value also acceptable

```

- rgba (red, green, blue, Alpha)

* red = 0 to 255 color range, (255 0 0)
* green = 0 to 255 color range, (0 255 0)
* blue = 0 to 255 color range, (0 0 255)
* Alpha = Alpha is define lightness of the color which range is from 1 to .001. 1 is full lightness and 0.001 is almost no color. 0 is colorless. There is many portion is between those range like .34985885 is also possible.  

```css

  color: rgba(0 255 0 / 0.5) // Here is green color with half lightness
  color: rgb(0 255 0 / 0.5) // Give same value if we not declare alpha attribute, but give alpha value

```

### Box Shadow

> A smart box Shadow Generator [Link](https://www.joshwcomeau.com/shadow-palette/)

