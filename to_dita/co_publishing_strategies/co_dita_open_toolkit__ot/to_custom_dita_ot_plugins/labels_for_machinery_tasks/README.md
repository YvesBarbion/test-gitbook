---
authorinformation: null
category: Reference Guide
---

# com.flow.machinerytask.labels

Labels for machinery tasks in HTML5 output.

The following elements in the machinery task topics require labels when published, but these labels are not added yet to the final output by the default DITA-OT plugins:

* `perscat`,
* `peronnel`
* `reqconds`
* `reqpers`
* `supeqli`
* `supplyli`

The com.flow.machinerytask.labels DITA-OT plugin adds these labels to your HTML5 output.

## Localization

By default only English labels are added to plugin.

Follow this procedure [Add extra languages to the plug-in](ta_add_more_languages_to_the_plugin.md) to add more languages.

## Making the labels visible

After installing the plug-in, the labels are still not only added to the final output. You need to set the DITA-OT parameter args.gen.task.lbl to YES to make them visible in the final output. As a consequence, also the labels of the following labels elements will be visible:

* `prereq`
* `context`
* `steps`
* `stepresult`
* `result`
* `postreq`

If you don't want to have labels for all elements, follow the procedure: [Undo labeling for standard task labels](co_labels_for_task_elements/ta_undo_labeling_task_labels.md).

**Related information**

