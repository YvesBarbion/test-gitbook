---
authorinformation:
  - null
  - Pieterjan Vandenweghe
  - Yves Barbion
keyword: null
---

# Preprocessing files in Microsoft Word

The **consistent** usage of styles in Microsoft Word is important for a smooth conversion from Microsoft Word to DITA. A style is a collection of formatting instructions which can be mapped to DITA elements. If no styles are used, you need to clean up the source DOCX and apply the Microsoft styles. It is important to already have DITA information models in mind when you do this.

Check the items described below before you convert the files:

## Title

Your document should start with a **Title** style in Word.

## Table of contents

You do not need to worry about the table of contents. The table of contents is discarded during conversions.

## Logical use of heading styles

Always check if the heading styles are used in a logical way. For example, **Heading 1** must be followed by another **Heading 1** if you want to start a new chapter or **Heading 2** if you want to start a subchapter, but can't be followed by a **Heading 3**. If this is the case, you should update the styles to be sure your conversion runs correctly. If the heading styles are not set correctly, this could lead to missing topics after conversion. In the mapping table we have to set the level of each topic and the conversion breaks if these levels have not been not set logically.

## Procedures

Procedures are the most difficult content type to convert. By default, all the topics are converted to a concept content type. When you describe a procedure, you use the task content type and while preprocessing the files we have to tell the code that you want convert a procedure to a task topic. You can do this by creating a new Microsoft style that you map in a later stage to a task.

For example, you use the style **Heading 2** for a concept file and you use a new style **Task Heading 2** for a task procedure at the same level. Or you use a **Heading 3** style for a concept file and **Task Heading 3** for a task procedure at the same level.

## Step versus ordered list

Make a difference between a step in a procedure and an ordered list where you describe a process. Afterward you can easily map them to the correct element in DITA.

## Notes

Notes are regularly preceded by an icon in a Microsoft Word document and/or are used in a table. Delete these icons before the conversion and convert the tables to text. When you have a document with a lot of notes, you can create a Word macro to automate this process a bit.

You should also create a style per type of note. For example, create a style **Tip** to convert it to the DITA element `note` where the `@type` attribute value is set to `tip`.

## Tables

Tables do not need to be preprocessed before converting them to DITA. Only very complicated tables with merged cells could lead to incorrect tables in DITA topics.

