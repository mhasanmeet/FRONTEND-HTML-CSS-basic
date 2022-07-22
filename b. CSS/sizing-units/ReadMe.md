## 𝗖𝗦𝗦 𝗨𝗻𝗶𝘁𝘀 (From Google www.Web.dev/learn/css)

CSS Unit are determines the size of a property of an element or its content

1. **Absolute Units**: Units that are "absolute" are the same size regardless of the parent element or window size.

| Absolute Units | Name | Equivalent to
|-|-|
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



