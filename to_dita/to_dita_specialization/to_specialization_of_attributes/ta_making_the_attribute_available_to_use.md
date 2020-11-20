---
authorinformation:
  - null
  - Pieterjan Vandenweghe
keyword: null
---

# Making the attribute available for use

We continue in the topic.dtd file.

1. Search for DOMAIN ATTRIBUTE EXTENSIONS.

   By default the extension looks like this:

   ```text
   <!ENTITY % props-attribute-extensions
     "
    %deliveryTargetAtt-d-attribute;
   "
   >
   ```

   The attribute `@deliverytarget` is already an extensions of the `@props` attribute.

2. Go to the next line and add `%` followed by the name of the attribute `ngs_system` and end with `Att-d-attribute;`.

   ```text
   <!ENTITY % props-attribute-extensions
     "
    %deliveryTargetAtt-d-attribute;
    **%ngs\_systemAtt-d-attribute;**
   "
   >
   ```

   **Note:** Each attribute should end with a semi-colon and all the attributes you want to add should be placed between the quotation marks. Do not add a space after %.

