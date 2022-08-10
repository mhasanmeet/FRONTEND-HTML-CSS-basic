## CSS Units

### Size Units
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
## CSS font's size issue solved by [Joshw Comeau](https://www.joshwcomeau.com/css/surprising-truth-about-pixels-and-accessibility/) 
### What is root font size? 

> The root font size is 16px

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




### COlor Units