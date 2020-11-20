---
authorinformation:
  - null
  - Pieterjan.vandenwegh
category: Reference Guide
keyword: null
---

# Installing a DITA-OT plug-in with Command Prompt

In this topic we use \[DITA-OT DIR\] as a variable for your DITA-OT folder.

1. Copy the new plug-in folder to the /plugins folder of your DITA-OT folder.
2. Open Command Promptvia the windows start menu.
3. Change the directory of the Command Prompt to the directory of the DITA open toolkit.

   You can change the directory with the `cd` variable.

   To change the directory, insert `cd C:\>cd C:\Program Files (x86)\DITAToo\Plugins\dita-ot-3.3\` and click enter.

   **Note:** Don't forget the back slash at the end of the filepath.

   ![](../../../../.gitbook/assets/commandline1.png)

   When the prompt directory is not the drive where the DITA-OT plug-in is installed, you first have to change the drive. You can do this by inserting the name of the drive followed by ":" and clicking enter.

   ![](../../../../.gitbook/assets/commandline2.png)

4. Insert `ant -f integrator.xml.` and click enter.

The plug-in you added in step [1](ta_installing_an_dita_ot_plug_in_with_command_prompt.md#step_srp_1n1_x3b) is added to the DITA-OT.

