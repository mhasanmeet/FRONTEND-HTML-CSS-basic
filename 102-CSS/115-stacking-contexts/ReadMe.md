# Z-index & Stacking order

Z-index refer to the z asix:

-> X is left/right
-> Y is up/down
-> Z is forward/backward

A good way to think about this is that elements with a higher z-index are placed closer to the viewer in 3D space, coming out of the screen.

The default value of the z-index property is auto, which is equivalent to the number 0. Therefore, any value greater than 0 can be used to "promote" an element to sit in front of its siblings.

## Negative Z-index

z-index values must be integers, and they're allowed to be negative.

```css
/* is a valid declaration. */
{ z-index: -1 }
```

Though, negative z-indexes introduce additional complexity without offering much benefit. that's why, it's better to not use.
