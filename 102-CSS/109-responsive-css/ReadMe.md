## Web Responsiveness

HTML is default web responsive, until we use CSS. Yeah, this is truth. Maybe it is look not stylish but it will show responsive behavior until we do custom css coding. 

### Some tips 

✔ If we want to get more responsive behavior then need to **use Percentage (%) in CSS size units**, instead of pixel (px) size units. 

✔ Careful when using % (percentage) size units. Parents % size units also affect child elements sizing. Root element have a default size. If we use % like size units from the first element then root % size units will not follow in middle child elements. 

✔ Instead of declaring height in pixel (px) we can use rem/em. 

💡 rem stands for root element and em stands for element. em is simply font size relevant element which is follow it's size from parent and rem is simply root element. The both default font size is 16px. If we use 1rem/1em without customizing the default font size then 1rem/em is actually 16px. 

## font

```css
    html {
        font-size: calc(0.75rem + 1.5vw);
    }

    html {
        font-size: clamp(1rem, 0.75rem + 1.5vw, 2rem);
    }
```

## Text line length
maximum 66 character in each line

```css
    article {
        max-inline-size: 66ch;
    }
```

## Using Custom font

```css
    @font-face {
        font-family: Roboto;
        src: url('/fonts/roboto-regular.woff2') format('woff2');
    }
        body {
        font-family: Roboto, sans-serif;
    }
```
--
### Suggested Courses and Readings

1. Kevin Powell's Conquering Responsive Layouts - [Conquering Responsive Layouts](https://courses.kevinpowell.co/view/courses/conquering-responsive-layouts)

2. Web Dev Responsive Design - [Web Dev Responsive Design](https://web.dev/learn/design/)



