---
authorinformation:
  - null
  - Pieterjan.vandenwegh
category: Reference Guide
keyword: null
---

# Labels for task elements

Task labels are by default not added to final output of a DITA project. When you want to have labels, you need to set the DITA-OT parameter args.gen.task.lbl to YES.

The following DITA elements will have a label in the final output when the args.gen.task.lbl is set to YES:

* `prereq`
* `context`
* `steps`
* `stepresult`
* `result`
* `postreq`

Even when you set the args.gen.task.lbl to YES, you may not want to have labels for all these elements, but only for specific elements. To do so, follow this procedure: [Undo labeling for standard task labels](ta_undo_labeling_task_labels.md).

