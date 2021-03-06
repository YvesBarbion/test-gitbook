---
authorinformation:
  - null
  - Kimberley.De.Moor
keyword: null
---

# Using content references \(conrefs\)

Content references \(conrefs\) are generally the smallest type of content re-use as you only reference a single element of your content. However, the size of the element may vary greatly from one word to an entire section.

You cannot conref loose bits of content; the text must always be embedded within its element tags. This is because text on its own cannot have an ID to reference, only elements can hold an ID. This also means you are bound by the DITA structure rules and need to re-use an element within its appropriate content. You cannot, for instance, conref a `step` element \(used only in task topics\) in a concept topic.

