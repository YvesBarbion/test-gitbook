---
authorinformation:
  - null
  - Pieterjan.vandenwegh
keyword: null
---

# Open each image in a separate HTML page

1. Create a new JAVASCRIPT file.
2. Paste this code in the JAVASCRIPT file:

   ```text
   $(document).ready(function(){

       $('img.image').click(function(){

           window.open($(this)[0].src, '_blank')

       });

   });
   ```

3. Add a link to the JAVASCRIPT file in the head of the H.

