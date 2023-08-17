## CSS clip

* css clip path 

```css

    /* default circles clip path */
    .container{
        clip-path: circle();
        clip-path: circle(50%);
    }


    /* animation tricks */
    .container{
        width: 500px;
        height: 500px;
        background-color: blueviolet; 
        clip-path: circle(50% at 0 0);  
        transition: .6s ease-in-out;
    }

    .container:hover{
        clip-path: circle(100%);
        transition: .6s ease-in-out;
    }


    /* Polygon clip path, here is a star design polygon clip path 
        We can also animate this as well
    */
    .container{
        clip-path: polygon(50% 0%, 61% 35%, 98% 35%, 68% 57%, 79% 91%, 50% 70%, 21% 91%, 32% 57%, 2% 35%, 39% 35%);
    }

```

* Clip path making website [Clippy](https://bennettfeely.com/clippy/)
* Clip path making by Figma & make animate