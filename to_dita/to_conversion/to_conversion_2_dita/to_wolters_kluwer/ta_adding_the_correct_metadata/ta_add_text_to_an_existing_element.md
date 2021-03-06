---
authorinformation:
  - null
  - null
category: null
keyword: null
---

# Add text to an existing element

Make sure to comment out all topics or chapters that do not need the metadata:

* Glossary
* All links in the frontmatter.

You run this procedure when the element is already present in the topic, but without content.

1. Open the DITAMAP in the **Text** mode in the OxygenXML editor.
2. Select all topics or DITAMAP files that do not need the metadata, right-click and choose **Toggle comment!**.
3. Right-click on the DITAMAP file and choose **Refactoring** &gt; **Replace element with XML content**.
4. Add the correct target element with Xpath in **Target elements \(Xpath\):**.

   //prolog//category

5. Add the correct text to be added in **XML Fragment:**.
6. Choose **Next**.
7. Choose the **Current DITA map hierarchy** option in **Scope**.
8. Choose **Preview**.
9. Preview the result and do one of the following:
   * Choose **Finish** is the preview is what you need.
   * Choose **Back** is the preview is not what you need and go back to step [4](ta_add_text_to_an_existing_element.md#step_j5d_5bp_jkb).

Open the DITAMAP file again in the editor and undo the commenting out.

