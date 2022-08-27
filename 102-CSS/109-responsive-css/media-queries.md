## Stylesheet for Print

```html
    <link rel="stylesheet" href="print.css" media="print">
```

## Query Condition

```html
    <link rel="stylesheet" href="specific.css" media="type and (feature)">
```

## Media Queries for screen orientation
```css
/*Media screen orientation Rule (landscape & Portrait) */
    @media (orientation: landscape){
        body{
            background: pink;
        }
    }

    @media (orientation: portrait){
        body{
            background-color: lightblue;
        }
    }

/* Or */

    @media all and (orientation: landscape){
        body{
            background: pink;
        }
    }

    @media all and (orientation: portrait){
        body{
            background-color: lightblue;
        }
    }
```
### Or separate Stylesheet

```html
    <link rel="stylesheet" href="landscape.css" media="all and (orientation: landscape)">
    <link rel="stylesheet" href="portrait.css" media="all and (orientation: portrait)">

    <!-- or -->

    <link rel="stylesheet" href="landscape.css" media="(orientation: landscape)">
    <link rel="stylesheet" href="portrait.css" media="(orientation: portrait)">
```

## Screen Display Mode with Media Rule

```css
    @media (display-mode: fullscreen){
        body{
            background: pink;
        }
    }

    @media (display-mode: browser){
        body{
            background: pink;
        }
    }

    @media (display-mode: minimal-ui){
        body{
            background: pink;
        }
    }
```

## Screen color mode based on OS (Computer Dark mode & Computer Light mode)

```css
    @media (prefers-color-scheme: dark) {
        body{
            background: pink;
        }
    }
    
    @media (prefers-color-scheme: light) {
        body{
            background: pink;
        }
    }
```

## Adjust styles based on viewport size

```css

    // Styles for viewports wider than 400 pixels.
    @media (min-width: 400px) {
        
    }

    //Styles for viewports narrower than 400 pixels.
    @media (max-width: 400px) {
        
    }

    //minimum width & height
    @media (min-width: 400px) and (min-height: 600px) {
        
    }
```