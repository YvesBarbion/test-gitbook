---
authorinformation: null
category: User Guide
---

# Adding refactoring operations to the Oxygen XML editor

Refactoring operations are an advanced Search and Replace. It will help you to do bulk changes without losing a lot of time. You can add these scripts to the general Oxygen XML framework or a custom framework to make it visible for everyone you collaborate with. A refactoring operation is always defined as a pair of resources:

* XSLT Stylesheet or XQuery update script with the code to update the file.
* An XML Operation Descriptor file that contains the general information about the script.
* Add the refactoring files \(script and descriptor file\) to the correct folder in your OxygenXML project.

  In the Flow bv context, we add these files in the custom framework folder structure.

  C:\Github\DITA\\_custom\_framework\dita\_extension\refactoring

* Choose **Options** &gt; **Preferences**.
* Go to **Document Type Association**, select your custom framework and click **Edit**.
* Under the **Classpath**, click ![](../../../../.gitbook/assets/oxy_icon_new%20%281%29.png).
* Add the URL to the refactoring operations and click **OK**.
* Click **OK** &gt; **Apply** &gt; **OK** to confirm the changes.

