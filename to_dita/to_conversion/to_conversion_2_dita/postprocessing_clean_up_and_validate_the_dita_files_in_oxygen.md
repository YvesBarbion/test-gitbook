---
authorinformation: null
---

# Step 4: Postprocessing — Clean up and validate the DITA files

## Validate and check for completeness

The first thing to do when the MIF files have been converted to DITA is to open the DITA map in Oxygen XML and to validate it, using the **Validate and Check for Completeness** button.

![](../../../.gitbook/assets/validate_button_dita_maps_manager2.png)

You may get a very long list or errors the first time you validate your DITA map and topics, but no stress. You can sort the list by clicking the **Description** column heading.

![](../../../.gitbook/assets/validation_errors.png)

You will then find many errors which occur frequently, mainly errors related to the content structure. These can usually be resolved all at once by improving the MIF2Go conversion routines and then running the conversion again \([saving the MIF files as DITA](conversion_save_the_mif_files_as_dita.md)\). This may be an [Iterative process](../../../to_glossary/iterative_process.md).

**Important:** It is important to fix these common errors with optimized conversion routines first **before** you start to check and clean up the individual DITA topics because the DITA topics will be overwritten each time you run the conversion routine.

## Clean up in Oxygen XML and PowerGREP

You can do some of the cleanup work in Oxygen XML but if you find yourself correcting the same errors repetitively, it may be a better idea to use PowerGREP actions to save time.

We \(well, Pieterjan actually\) have already developed a number of these actions, which you can then simply run on a set of DITA files. For more information on PowerGREP, see Pieterjan.

