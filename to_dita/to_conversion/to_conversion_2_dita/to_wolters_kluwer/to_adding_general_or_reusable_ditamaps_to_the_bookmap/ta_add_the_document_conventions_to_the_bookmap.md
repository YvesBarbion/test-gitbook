---
authorinformation:
  - null
  - null
category: null
keyword: null
---

# Add the Document Conventions to the BOOKMAP

1. In the **DITA Maps Manager**, in your bookmap: select the white arrow to the left of **Frontmatter**.
2. Under **Frontmatter**, right-click **booklists** and select **Insert Before** &gt; **References...**.

   ![](../../../../../.gitbook/assets/adjusting_attributes_doc_conventions_1.png)

   The Insert Topic Reference window opens.

3. Look for the \_conventions folder in the 03\_dita folder, open it and select \_conventions.ditamap.
4. Select **Insert and close**.
5. Right-click **Conventions** in the **DITA Maps Manager** and select **Edit Properties...**.

   The Edit Topic Reference Properties window opens.

6. Go to the **Attributes** tab and search for the `@deliveryTarget` attribute in the list of attributes.
7. Select the value **print** for the `@deliveryTarget` attribute and select **OK**.

   ![](../../../../../.gitbook/assets/adjusting_attributes_doc_conventions_2.png)

   The text **deliveryTarget \[print\]** will appear next to the **Conventions** ditamap in the **DITA Maps Manager**.

   ![](../../../../../.gitbook/assets/adjusting_attributes_doc_conventions_3.png)

8. Open the bookmap in the OxygenXML editor in **Text** mode.
9. Search for the **Conventions** ditamap which has been added as a `topicref` element in the bookmap.

   ![](../../../../../.gitbook/assets/adjusting_attributes_doc_conventions_4.png)

10. Change the `topicref` element to a `preface` element and save your changes.

    ![](../../../../../.gitbook/assets/adjusting_attributes_doc_conventions_5.png)

