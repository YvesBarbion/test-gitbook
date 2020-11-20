---
authorinformation:
  - null
  - Pieterjan.vandenwegh
category: Reference Guide
keyword: null
---

# Undo labeling for standard task labels

By default the task labels are not added to final output of a DITA project. When you want to have labels, you need to set the DITA-OT parameter args.gen.task.lbl to YES.

The following DITA elements will have a label in the final output when the args.gen.task.lbl is set to YES:

* `prereq`
* `context`
* `steps`
* `stepresult`
* `result`
* `postreq`

You may not want to have labels for all these elements, but only for specific elements. To do so, follow this procedure:

1. Open the XSL file you are working in.

   xsl/machinerytasklabel.xsl

2. Add the following code to the XSL file: `<xsl:template match="*[contains(@class, 'XXXX')]" mode="generate-task-label"/>` where XXXX matches the class of your element.

   To override the label for the `context`, you add this code: `<xsl:template match="*[contains(@class, 'task/context ')]" mode="generate-task-label"/>`

   You can find the correct code to override all task labels in the processing instructions of the file com.flow.machinerytask.labels/xsl/machinerytasklabel.xsl.

3. Save the file.

When you set the args.gen.task.lbl to YES, DITA-OT will show all labels unless you overrode them with the above code.

If you want to have to labels for all task elements, except `prereq`, you do the following:

1. Open the XSL file of the plug-in you use, for example machinerytasklabel.xsl.
2. Add this code: `<xsl:template match="*[contains(@class, 'task/prereq ')]" mode="generate-task-label"/>` to the file.
3. Save the file.
4. Open the DITA transformation scenario you want to run with this new code.
5. Set the DITA-OT parameter args.gen.task.lbl to YES.
6. Run the DITA transformation scenario.

