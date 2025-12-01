# CSS Grid & Flexbox

In CSS layout, bellow three are different ways the browser arranges elements on the page.

1. Normal Flow

    This is the default layout behavior, if you don’t use Flexbox, Grid, floats, or positioning.

    For **Block elements** it works as,

    * Take the full available width
    * Stack vertically, one after another

    For **Inline elements** it works as,

    * Only take as much width as their content
    * Flow horizontally in a line
    * Wrap to the next line when there is no space

    When it is used?

    * By default, in any HTML.
    * When you’re not using layout systems like flex/grid.
    * Simple pages, blog posts, text content.

2. Flexbox and
3. Grid

## CSS Grid

Important Properties

```css

    display: grid;
    place-items: center; (Justtify content: center & Align Items: center)

```

Tricks

```css

    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));

```

## CSS Flexbox

Important CSS Flexbox properties

```css

    display: flex;
    align-items: start | center | end | flex-start | flex-end;
    
    /*Baseline alignment*/
    align-items: baseline;

    /*Global Values alignment*/
    align-items: inherit | initial | revert | revert-layer | unset;

    /*Justify content*/
    justify-content: center | start | end | left | right; 

```

---
Resources

1. 🔴 Video Source — [Grid Tutorial](https://www.youtube.com/watch?v=kEFIdXzQXYw)
2. 🔴 Video Source — [Modern Layout Hacks from web.dev](https://1linelayouts.glitch.me/)
