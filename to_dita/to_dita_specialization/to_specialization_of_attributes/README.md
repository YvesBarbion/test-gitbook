---
authorinformation:
  - null
  - Pieterjan Vandenweghe
keyword: null
---

# Specialization of conditional formatting attributes

The standard DITA information architecture comes with a default set of conditional processing attributes:

* `@product`
* `@audience`
* `@platform`
* `@otherprops`
* `@props`
* `@rev`

In some cases this set of attributes is not enough to suit your needs. In that case you can extend the number of filtering attributes with a custom DITA-OT plug-in.

You can create a DITA-OT plug-in with extra conditional filtering attributes when you follow this process:

1. [Creating extra conditional filtering attributes](ta_creating_a_specialization_with_extra_conditional_filtering_attributes.md)
2. [Declaring the attribute in your content type](ta_adding_extra_filtering_attributes_to_topics.md)
3. [Making the attribute available for use](ta_making_the_attribute_available_to_use.md)
4. [Declaring the attribute as a conditional attribute](ta_declaring_the_attribute_as_a_conditional_attribute.md)
5. [Declaring files in the DITA catalog file](declaring_files_in_the_dita_catalog.md)
6. [Declaring the DOCTYPE in the topic templates](ta_declaring_the_doctype_in_the_topic_templates.md)

The process explains the workflow for one content type. You have to repeat steps [2](./#li_lfb_r2w_2lb) through [6](./#li_k44_r2w_2lb) for all content type this specialization applies to.

