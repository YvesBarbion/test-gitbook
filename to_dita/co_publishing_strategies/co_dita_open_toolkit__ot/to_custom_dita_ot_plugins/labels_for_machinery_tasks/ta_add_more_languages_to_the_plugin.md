---
authorinformation:
  - null
  - Pieterjan.vandenwegh
category: Reference Guide
keyword: null
---

# Add extra languages to the plug-in

Labels are not by default translated in all languages in the output files.

Proceed as follows to add translated labels to your output files in the non-default languages:

1. Go to the \resources\localization folder in the plug-in.
2. Make a copy of the file strings-en-us.xml.
3. Rename the file to strings-\[lang\].xml.

   Replace \[lang\] with the language code of the language you want to translate.

   strings-nl-nl.xml

4. Translate all the labels in this file.
5. Open the file strings.xml which you can find in the same folder.
6. Nest an extra `lang` element in the `langlist` element with the following attributes and values:

   | Attribute | Value |
   | :--- | :--- |
   | `xml:lang` | Official language code of the language you translated. |
   | `filename` | Link to the xml file you translated. |

   ```text
   <langlist>
   <lang xml:lang="nl-nl" filename="strings-nl-nl.xml"/>
   </langlist>
   ```

7. Save the file.
8. Open Oxygen XML as administrator and run the transformation scenario **Run OT integrator**.

The labels will be translated when the `xml-lang` in your topic attribute matches one of `xml:lang` in the strings.xml.

