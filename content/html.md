---
title: 'HTML:'
date: 2022-11-15T00:45:43-05:00
draft: true
menu: 'mainmenu'
---

---

### Document Structure

- **DOCTYPE**: lets the web browser know it's ok to use the most modern version of HTML
- **html**: root of the document
  - **head**:
    - **meta**: specifies character set
      - UTF-8 is for generally used for English
    - **title**: tab and site title
  - **body**:
    - **headers**:
      - h1, h2, h3, h4, h5, h6 (descending order)
    - **paragraph**
      - just p

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Example Page</title>
  </head>
  <body>
    <h1>Sample Landing Page</h1>
    <p>
      Paragraph with only one sentence.
    </p>
  </body>
</html>
```

---

### Linking Pages

- **a**: tag for a link
  - **href**: requires the <u>hypertext reference attribute</u>

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Homepage</title>
  </head>
  <body>
    <h1>Homepage</h1>
    <p>
      Welcome to the homepage. Learn more about my
      <a href="favorite-languages.html">favorite language</a>
      .
    </p>
  </body>
</html>
```
