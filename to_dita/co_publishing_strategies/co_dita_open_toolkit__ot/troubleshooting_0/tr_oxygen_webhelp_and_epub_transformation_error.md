---
authorinformation:
  - null
  - Kimberley.De.Moor
keyword: null
---

# Oxygen Webhelp and EPUB transformation error

## Condition

When publishing a project using a transformation scenario, you might see an error message like this:

![](../../../../.gitbook/assets/epub.jpg)

## Cause

It is possible that the language you are writing in, is not defined in Oxygen XML. In that case, words such as Chapter, Search and Part might not be translated when creating output.

## Remedy

1. In order to have a completely localized webhelp or EPUB file, follow this procedure:
2. Make sure that all the topics in your project have the correct `@xml:lang` attribute.
3. Look for the strings-\[lang1\]-\[lang2\].xml file in DITA-OT-DIR/plugins/oxygen-webhelp-responsive/resources/localization folder.

   The Canadian French file would be: strings-fr-ca.xml.

4. If the strings-\[lang1\]-\[lang2\].xml file does not exist, use the following procedure to create one:
   1. Copy the …/localization/strings-en-us.xml file. Change the name and open it.
   2. Add all the labels found in the DITA-OT\_DIR/xsl/common/strings-en-us.xml file and paste them into your file.
   3. Translate all the labels from the above language file. Labels are stored in XML elements that have the following format: `<str name=“Label name”>Caption</str>`.
   4. Add the new language to the strings.xml file in the localization folder by adding `<lang xml:lang=“nl-nl” filename=“strings-[lang1]-[lang2].xml”/>`.
5. Run Oxygen as administrator and run the predefined transformation scenario called **Run DITA OT Integrator** by executing it from the Apply Transformation Scenario\(s\) dialog box.

   **Note:** If the integrator is not visible, select the **Show all scenarios** action that is available in the **Settings** drop-down menu.

6. Edit the **WebHelp transformation scenario** and set theargs.default.language parameter to the code of the language you want to localize.

   fr-ca for Canadian French

7. Run the transformation scenario to produce the WebHelp output.

