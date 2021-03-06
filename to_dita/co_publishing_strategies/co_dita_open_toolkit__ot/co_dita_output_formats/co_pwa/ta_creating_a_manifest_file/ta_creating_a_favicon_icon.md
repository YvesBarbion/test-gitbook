---
authorinformation:
  - null
  - Pieterjan Vandenweghe
keyword: null
---

# Creating an ICO file

A favicon.ico file is a website icon containing one or more small icons. Browsers that support favicon display a favicon image in the browser's address bar. The favicon could also contain icons for mobile devices and based on the browser or device the favicon will show the correct image.

1. Go to a [Favicon converter](https://favicon.io/favicon-converter/) website.
2. Upload the logo image you want to convert.
3. Download the ZIP containing the ICO file.
4. Extract the ZIP and paste all images in the root folder of your website.
5. Add the link tags to the `head` element of your index.html

   ```text
   <head>
   ...**
   <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png"\>
   <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png"\>
   <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png"\>**
   ...
   </head>
   ```

