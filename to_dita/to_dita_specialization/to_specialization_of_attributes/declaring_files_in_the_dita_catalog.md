---
authorinformation: null
---

# Declaring files in the DITA catalog file

When you create the DITA-OT plug-in you have to declare which files are added to the plug-in. You can do this in a so-called dita-catalog.xml file.

1. Do one of the following:
   * Create a new XML file and go to step [2](declaring_files_in_the_dita_catalog.md#step_p3c_btv_2lb).
   * Open the dita-catalog.xml file you created in the procedure [Creating extra conditional filtering attributes](ta_creating_a_specialization_with_extra_conditional_filtering_attributes.md) and go to step [3](declaring_files_in_the_dita_catalog.md#step_yvc_ftv_2lb).
2. Add the following header to the file:

   ```text
   <?xml version='1.0' encoding='UTF-8'?>
   <catalog prefer="public" xmlns="urn:oasis:names:tc:entity:xmlns:xml:catalog">
   ```

3. Add the `public` element with two attributes:

   | Attribute | Description | Example |
   | :--- | :--- | :--- |
   | `@publicId` | The Public ID of the content type. | "-//FLOW BVBA//DTD Agilent DITA specialization topic//EN" |
   | `@uri` | Link to the file in the plug-in | dtd/topic.dtd |

   `<public publicId="-//FLOW BV//DTD Agilent DITA specialization topic//EN" uri="dtd/topic.dtd"/>`

   The `@publicId` is the declaration you will also use in the DOCTYPE declaration of each content type you want to use.

4. Do this for all DTD and ENT files in the plug-in.

   The `@publicId` should be different for each file you declare.

   ```text
   <?xml version='1.0' encoding='UTF-8'?>
   <catalog prefer="public" xmlns="urn:oasis:names:tc:entity:xmlns:xml:catalog">
   <public publicId="-//FLOW BVBA//DTD Agilent DITA specialization topic//EN" uri="dtd/topic.dtd"/>
   <public publicId="-//Flow BV//ENTITIES DITA Manufacturer Attribute Domain//EN" uri="dtd/manufacturerAttDomain.ent"/>
   <public publicId="-//Flow BV//ENTITIES DITA Ngs_system Attribute Domain//EN" uri="dtd/ngs_systemAttDomain.ent"/>
   </catalog>
   ```

