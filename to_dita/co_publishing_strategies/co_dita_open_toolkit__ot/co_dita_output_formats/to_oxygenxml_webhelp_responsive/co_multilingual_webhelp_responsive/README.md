---
authorinformation:
  - null
  - Pieterjan Vandenweghe
keyword: null
---

# Multilingual WebHelp responsive

When the documentation is available in several languages, you can to create a multilingual webhelp where the readers can easily switch between languages depending on their favorite language. This is not possible with the standard **DITAMAP Webhelp Responsive** transformation scenario in Oxygen XML, but you can get this done by adding an extra JAVASRIPT file created by Flow bv created with the help of CleverWeb. This script only works perfectly in the following cases:

* All files from one webhelp \(=language\) are stored in a standardized language folder.
* All files with the same content have the same file name in all languages.

**Note:** HTML files are generated in the same folder structure \(per language\) as the folder structure of your documentation. Some writers works with subfolders, others work with one main folder. In general, the script will work for both scenarios. Only a subfolder with the same folder name as a language folder will result in a corrupt script.

## Folder structure multilingual responsive webhelp

```text
nl
   index.html
   topica.html
...topicb.html
fr
   index.html
   topica.html
...topicb.html
de
   index.html
   topica.html
...topicb.html
es
   index.html
   topica.html
...topicb.html
```

## Customizing the language selector

Download the latest version of the language selector JAVASCRIPT file [here](https://github.com/Flow-Technical-Communication/DITA/tree/master/Oxygen/Webhelp-Responsive/javascript/language_selector).

The language selector makes it possible to switch between languages \(folders\), but it only works properly when you define all languages and their folder names. You have to update the script when you add or delete a language.

1. Open the language\_selector.js with a text editor.
2. Search for `var LANG_CHOICES`.

   You find the default languages between the square brackets: `[["de", "DE"], ["en", "EN"]]` where:

   * "en" is the name of the language folder in your folder structure.
   * "EN" is the text you want to see in the drop-down list in your HTML.

3. Follow the same logic to add all the necessary languages.

   When you want to add a folder with French files to the file and your files are stored in a fr folder, the final result should be:

   `var LANG_CHOICES = [["de", "DE"], ["en", "EN"], ["fr", "FR"]];`

   **Note:** Do not delete the ; at the end of the line.

4. Store this file together in the customization folder of your project.

   \_custom\_framework\webhelp\flow\resources\js

To add this JAVASCRIPT file to the Webhelp responsive, you have to follow this procedure: [Creating a valid XHTML file with the extra head information](../adding_extra_info_to_the_head_of_html_pages/).

