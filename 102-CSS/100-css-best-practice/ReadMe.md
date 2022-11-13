## CSS best practice

* Use separate file for custom & screen breakpoints properties
* use separate css file for each page, so that the whole css file will not load at a time
* use Lazy load for image properties
* use your own `css normalize` code if possible

### font
* use font in locally

### Color
* use `hsl color` code for easy and maintainable color palette

### Size
* use `rem` for css size
* use `clamp` css function for typography sizing

```css

    h1{
        font-size: clamp(28px, 16px + 2vw, 40px); //minimum size, variable size, maximum size
    }

```

