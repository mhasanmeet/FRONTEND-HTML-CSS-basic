# SVG

## SVG Line

In SVG the most straightforward shape is <line>
![SVG line](./img/svg-line.png)

## Rectanges

Rectangles are positioned using their top/left corner, specified using x and y. They grow from that size, using width and height.
![SVG Rect](./img/svg-rect.png)

Stroke is drawn on the center of the path, not on the inside or the outside.
![SVG Stroke](./img/svg-stroke.png)

**Round Corner:** ound the corners of our rectangle using the rx and ry properties, similar to border-radius.
![SVG border round](./img/svg-border-round.png)

## Circle

The size of a circle is dictated by its radius, r. We control the position of the circle by specifying a center point with cx and cy.
![SVG circle](./img/svg-circle.png)

## Ellipses

An <ellipse> is just like a <circle>, except we can choose different values for its horizontal and vertical radius. This lets us create ovals.
![SVG ellipse](./img/svg-ellipse.png)

## Polygon

The <polygon> element lets us create multi-sided shapes. The points attribute takes a list of X/Y points; the browser will draw a line between each point.
![SVG polygon](./img/svg-polygon.png)

## Read More

* [A Friendly Introduction to SVG by Joshw Comeau](https://www.joshwcomeau.com/svg/friendly-introduction-to-svg/)
