---
authorinformation:
  - null
  - Pieterjan Vandenweghe
keyword: null
---

# Conversion to DITA with Mif2GO

## The conversion process

The main stages in the conversion process are as follows:

![](../../../.gitbook/assets/conversion2dita.svg)

1. [**Preprocessing**](preprocessing_clean_up_the_source_files/): Open or import the Word file in FrameMaker 2019 or later versions and clean up.
2. [**Conversion**](conversion_save_the_framemaker_files_as_mif_maker_interchange_format.md): Save the FrameMaker files as MIF \(Maker Interchange Format\).
3. [**Conversion**](conversion_save_the_mif_files_as_dita.md): Open the MIF files FrameMaker 11 and save them as DITA, using MIF2Go.
4. [**Postprocessing**](postprocessing_clean_up_and_validate_the_dita_files_in_oxygen.md): Clean up and validate the DITA files.

Each of these stages has a number of things which need to be checked and fixed. These are described in the following topics.

## Why FrameMaker?

It may seem a bit strange to use FrameMaker to convert Word files to DITA. We use this intermediate step for the following reasons:

* We are using an old but very powerful conversion plug-in for FrameMaker 11: MIF2Go. We know that there are other DITA conversion tools around, but we haven't found a better alternative for MIF2Go yet.
* Some content cleanup actions are easier to do with FrameMaker than with Word, for example remapping styles \(a.k.a. character formats, paragraph formats, table formats etc.\).

