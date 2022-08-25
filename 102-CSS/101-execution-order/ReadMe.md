## CSS Execution Order

CSS Execution Order is one of the important topic that any developer should care about it. It is define 
the css behavior and basic execution rule.

### Cascade Order (From Google www.Web.dev/learn/css)

CSS stands for Cascading Stylesheets. The cascade is the algorithm for solving conflicts where multiple CSS rules apply to an HTML element.

**The cascade algorithm is split into 4 distinct stages**

1. Position and order of appearance: the order of which your CSS rules appear
2. Specificity: an algorithm which determines which CSS selector has the strongest match
3. Origin: the order of when CSS appears and where it comes from, whether that is a browser style, CSS from a browser extension, or your authored CSS
4. Importance: some CSS rules are weighted more heavily than others, especially with the !important rule type

### Origin of CSS 

The CSS that you write isn't the only CSS applied to a page. The cascade takes into account the origin of the CSS. This origin includes the browser's internal stylesheet, styles added by browser extensions or the operating system, and your authored CSS. The order of specificity of these origins, from least specific, to most specific is as follows:

1. User agent base styles. These are the styles that your browser applies to HTML elements by default.
2. Local user styles. These can come from the operating system level, such as a base font size, or a preference of reduced motion. They can also come from browser extensions, such as a browser extension that allows a user to write their own custom CSS for a webpage.
3. Authored CSS. The CSS that you author.
4. Authored !important. Any !important that you add to your authored declarations.
5. Local user styles !important. Any !important that come from the operating system level, or browser extension level CSS.
6. User agent !important. Any !important that are defined in the default CSS, provided by the browser.

![Origin of CSS](./Images/origin-of-css.svg)

### Specificity Order (Execution Priority Order)

1. Inline CSS -- Most execution Priority, inline CSS is not recommended
2. #ID selectors -- Next most execution Priority, standard to write css
3. .class, :pseudo-class, [attributes] -- Next most execution Priority, class selector is standard to write general css code
4. Tag and ::Pseudo-element selectors -- low level execution Priority
5. universal Selector ( * ) -- Zero (0) level execution Priority

1. !important -- Avoiding and overriding, it is use to overriding css code, top level execution Priority

![specificity](./Images/visualizing-specificity.svg)

### Importance

Not all CSS rules are calculated the same as each other, or given the same specificity as each other.

The order of importance, from least important, to most important is as follows:

1. normal rule type, such as font-size, background or color
2. animation rule type
3. !important rule type (following the same order as origin)
4. transition rule type