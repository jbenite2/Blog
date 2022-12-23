---
title: "CSS:"
date: 2022-12-23T12:33:00-04:00
draft: false
---

---

### Linking CSS with HTML

- ##### Add to HTML file in the head section:
    - **link**: link tag
        - **rel**: relationship attribute set as "stylesheet"
        - **href**: location of the CSS document
- ##### CSS basics:
    - <u>Rule</u>: styled output for a section
        - <u>Selector</u> = selector elements tell css which section to style
        - <u>Declaration(s)</u> = different ways you can modify a section

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Example Page</title>
    <link rel="stylesheet" href="css/screen.css">
  </head>
  <body>
    <h1>Sample Landing Page</h1>

    <p>
      Paragraph <span>with</span> only one sentence.
    </p>

    <p class="special-p">
      Paragraph <span>with</span> only one sentence.
    </p>

  </body>
</html>
```


```css

/* file: css/screen.css */

h1 {
    color: orange;
    text-align: center;
}

p {
    color: green;
}

```

---

### CSS Selectors
- <u>Type selectors:</u> name of an element and targets every element with that selector in a page. 
- <u>Descendant selectors:</u> drilling into a subsection to modify it further
- <u>Class selectors:</u> special cases where you can't use a type selectors. Specify the class in the tag you want to change and make sure to initialize the selector with a period. 
```css

/* file: css/screen.css */

/* Type selectors */
h1 {
    color: orange;
    text-align: center;
}

/*Descendant selectors*/
body p span{
    color: green;
}

/* Class selectors */
.special-p {
    background-color: yellow;
}

/* You can mix them all */
body .special-b{
    background-color: LightGray;
}


'''


