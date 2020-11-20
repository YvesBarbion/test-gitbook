---
authorinformation:
  - null
  - Pieterjan Vandenweghe
keyword: null
---

# Adding the FluidTopics plugin to DITAToo

Close DITAToo Author before you start this procedure.

1. Go to this folder on the server: S:\IT\DITAToo\PluginFluidTopics.

   In this folder you find two DLL files:

   * FluidTopicsAdvanced.dll
   * FluidTopicsPluginConfig.xml

2. Copy the two DLL files and paste it in the Plugins folder of your DITAToo Author installation.

   C:\Program Files \(x86\)\DITAToo\Plugins

3. Open the FluidTopicsPluginConfig.xml file and add your FluidTopics login information in the `url`, `username` and `password`.

   ```text
   <FluidTopicsConfig>
   <url>https://my.fluidtopics.net/flowtime01/</url>
   <username>pierrejean.delaroute@flowtime.be</username>
   <password>AllezLesMauves</password>
   </FluidTopicsConfig>
   ```

4. Save the file.

You will find a **FluidTopics** menu in the main menu of DITAToo Author when you open the application.

