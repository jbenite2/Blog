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


---
### Video
- **video**: image tag
  - **controls**: shows pause play volume options
- **source**: source tag
  - **src**: attribute where you specify the location of the video 
  - **type**:  specify the video  type


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
      This is a video file:
      <video controls>
        <source src="video/example.mp4" type="video/mp4"> //Browser should pick this one
        <source src="video/example.webm" type="video/webm"> //If it doesn't recognize mp4 it'll pick this one
        <source src="video/example.ogv" type="video/ogg"> //If none of the other ones work it'll pick this one
        Your web browser if outdated and does not support HTML video. Please consider <a href="http://browsehappy.com/">updating</a>. 
      </video>  
    </p>
  </body>
</html>
```


---
### Vector Graphics
What is a vector graphic? It's basically an image that doesn't loose quality when zooming in. It's comprised of adjustable shapes. 

**Figma** and **XD** are good resources for vector graphics. 

Append either by copy pasting the contents into the code or by referencing the image using svg as the type. 

"