---
authorinformation:
  - null
  - Pieterjan Vandenweghe
keyword: null
---

# Flow bv Schematron summary file

All the different Schematron checks summed in [Flow bv Schematron checks](co_flow_style_guide.md) are bundled in one file styleguide.sch. In this file you don't find any rule, only a reference to the different Schematron rules.

This summary file has the following advantages:

* If you add this one file as a validation check, all other checks will also performed automatically on the condition that the referenced files are in the exact same folder.
* If you add a check, you only have to add a reference to the new check in styleguide.sch and it will be checked automatically from that moment on.

