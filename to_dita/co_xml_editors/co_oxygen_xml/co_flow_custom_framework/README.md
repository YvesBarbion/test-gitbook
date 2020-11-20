---
authorinformation:
  - null
  - Pieterjan Vandenweghe
category: User Guide
keyword:
  - Standardization
  - Oxygen XML
---

# Flow bv custom framework

## About the custom framework

The Flow bv custom framework is a predefined folder structure to write multilingual DITA documentation in a efficient way. These are the default folders:

| Main folder | Subfolder 1 | Subfolder 2 | Description |
| :--- | :--- | :--- | :--- |
| \_documentation |  |  | Folder to save all BOOKMAP files and overall DITAMAP files from all languages. |
|  | \_custom\_framework |  | Folder to save all Oxygen XML related settings. |
|  | \_ditaval |  | Folder to save all the DITAVAL files. |
|  | \_graphics |  | Folder to save all language independent images. |
|  | \_output |  | Folder to save all publications. |
|  | \_subject\_scheme |  | Folder to save the subjectScheme file. |
|  | en |  | Folder to save all English DITAMAP files and topics. |
|  |  | \_graphics | Folder to save all language dependent images. |
|  |  | \_variable\_content | Folder to save product specific variables. |
|  |  | \_warehouse | Folder to save the files for re-use across all your DITA files. |
|  | de, fr and nl |  | Folder to save all DITAMAP files and topics for these particular languages. |

The custom framework is on top of that a handy customization of an Oxygen XML framework with predefined settings, such as:

* Topic templates
* Oxygen XML webhelp responsive template
* MiramoPDF template
* Transformation scenarios with standardized output folders
* Schematron checks
* Toolbar

## Oxygen XML project file \(\*.xpr\)

In the root folder \_documentation you find the Oxygen XML project file: klant.xpr. Using this file has a lot of advantages, such as:

* You can store all project related information, for example settings, code templates and transformation scenarios.
* You can run batch validations and batch publications.
* You can run a search and replace on project level.
* You can define master files which will be updated and relinked when you rename topics or move topics to another folder.
* When you open the XPR file in Oxygen XML, it will also open all the files that you had open in the project the previous time you used it.

**Tip:** Make sure this project file is opened at any time in Oxygen XML.

## Advantages of a custom framework

Using the custom framework has the following advantages:

* The custom framework is a kind of a template. You can start your project immediately with all settings and structures set correctly from the start.
* You can easily collaborate with colleagues in the same project without having to doubt if anyone is following the correct rules.
* You can easily take over a project from colleagues if they are absent for a while since everyone is using the same basic structure.

