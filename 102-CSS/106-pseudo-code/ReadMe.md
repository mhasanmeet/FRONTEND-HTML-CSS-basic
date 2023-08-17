## Pseudo Code 

### Pseudo Element (::)

1. ::after, ::before
2. ::first-letter, style of the first character of the target property
3. ::first-line, style of the first line of the target property
4. ::marker, style of the browser maker property
5. ::selection, style of the selected text
6. ::placeholder, style for placeholder texts
7. ::cue, Style for video captions
### ::before & ::after
- Without `content: " ";` css, ::before or ::after pseudo element will not take effect
- Pseudo Element is actually take effect inside before and after of the element. here is an example,

```html

    <P>
        ::before (::before pseudo element take effect in here in paragraph text)

        Hello World

        ::after (::after pseudo element take effect in here in paragraph text)
    </p>

```
- Pseudo element will not take effect in **image element**

🔴 Video Source — [video](https://www.youtube.com/watch?v=zGiirUiWslI)

### Pseudo Class (:)

### :has Pseudo Class 

sample code

```css

    list:has(p){
        code here...
    }

```

1. :has(p)
2. :has(p+p)
3. :has(*:only-child)

🔴 Video Source — [video](https://www.youtube.com/watch?v=OqLquBs-bEg)

## :is, :where, :not pseudo classes




