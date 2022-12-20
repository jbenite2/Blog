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

---
### Images
- **img**: image tag
  - **src**: attribute where you specify the location of the image 
  - **alt**:  attribute that serves as a basic description of the image (alternative text)


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
      <img src= "image.png" alt="description of image">
    </p>
  </body>
</html>
```

---
### Audio
- **audio**: image tag
  - **controls**: shows pause play volume options
- **source**: source tag
  - **src**: attribute where you specify the location of the audio 
  - **type**:  specify the audio type


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
      This is an audio file:
      <audio controls>
        <source src="audio/song.mp3" type="audio/mpeg"> //Browser should pick this one
        <source src="audio/song.ogg" type="audio/ogg"> //If it doesn't recognize mpeg it'll pick this one
        <a href="audio/song.mp3"></a> //Alternative for outdated browsers 
      </audio>  
    </p>
  </body>
</html>
```