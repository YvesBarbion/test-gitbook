---
authorinformation: null
---

# Adding an image to a tile on the home page

Choose an OxygenXML responsive webhelp template using tiles

1. Open your DITAmap
2. Add the `topicmeta` element to the `topicref` element
3. Add a `Data` element in the `topicmeta` element with the attribute `name` = wh-tile
4. Add a nested `data` with the following attributes:

   \|`name`\|image\| \|`href`\|Link to your image\| \|`format`\|The format of your image\|

   ```text
   <topicref href="user_guide.dita">
   <topicmeta>
   <data name="wh-tile">
   <data name="image" href="documentation/en/_graphics/user_guide_v2.png" format="png"> </data>
   </data>
   </topicmeta>
   ```

5. Publish your responsive webhelp

![](../../../../../.gitbook/assets/webhelp_tiles_with_images.png)

