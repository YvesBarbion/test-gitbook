---
authorinformation:
  - null
  - Pieterjan Vandenweghe
category: User Guide
keyword: null
---

# Getting started with the Flow bv custom framework

Once you created the GitHub project, you can personalize the default structure without changing the general principles.

1. Rename klant.xpr into the customer's name.

   flow.xpr

   **Note:** Do not use the project number as file name since we will use this XPR file for all projects of this customer.

2. Go to the \_custom\_framework/dita\_extension folder and open the FRAMEWORK file with a text editor, for example NotePad++.
   1. Search for Flow and replace it with the customer's name.
   2. Save the file.
   3. Rename the file: replace flow with the customer's name.
3. Go to the \_custom\_framework/topic\_templates folder and replace \_klant in all files with the customer's name.
4. Go to the \_custom\_framework/miramo folder and replace the default.mfd with the customer's name.
5. Open Oxygen XML and choose **Options** &gt; **Preferences**.
6. Go to **Document Type Association**, select your custom framework and click **Edit**.
7. Under the **Transformation** tab:
   1. Select **Miramo PDF - customer name**.
   2. Click ![](../../../../.gitbook/assets/oxy-edit-button.png).
8. Under the **Parameters** tab:
   1. Double-click mmpdf:mfd.file.
   2. Change the name of the MFD file to the name of step [4](ta_getting_started_with_the_flow_custom_framework.md#step_slz_tnw_jlb).
   3. Click **OK**.
9. Click **OK** &gt; **Apply** &gt; **OK**.

