---
authorinformation:
  - null
  - null
category: null
keyword: null
---

# Add the Glossary to the BOOKMAP

1. In the **DITA Maps Manager**: choose a position near the end of the bookmap to insert the glossary.
   * If you select the ditamap that is supposed to precede the glossary: right-click it and select **Insert After** &gt; **Reference...**.
   * If you select the ditamap that is supposed to follow the glossary: right-click it and select **Insert Before** &gt; **Reference...**.

     The Insert Topic Reference window opens.
2. Look for the \_glossary folder in the 03\_dita folder, open it and select \_glossary.ditamap.
3. Select **Insert and close**.
4. Right-click **Data Dictionary Glossary** in the **DITA Maps Manager** and select **Edit Properties...**.

   The Edit Topic Reference Properties window opens.

5. Go to the **Attributes** tab and search for the `@deliveryTarget` attribute in the list of attributes.
6. Select the value **print** for the `@deliveryTarget` attribute and select **OK**.

   ![](../../../../../.gitbook/assets/adjusting_attributes_doc_conventions_2%20%281%29.png)

