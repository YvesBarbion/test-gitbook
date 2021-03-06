---
authorinformation:
  - null
  - null
category: null
keyword: null
---

# Make sure that certain DITAMAPS do not appear in the final \(published\) result

To make sure that your warehouse, subject scheme, external links and keys ditamaps are not present in the final \(published\) document, you need to make sure that they are given the attribute value **resource-only**.

1. To do this:
2. Right-click on the warehouse, subject scheme, external links or keys ditamap in the **DITA Maps Manager** and select **Edit Properties...**.

   The Edit Topic Reference Properties window opens.

3. Go to the **Attributes** tab and search for the `@processing-role` attribute in the list of attributes.
4. Select the value **resource-only** for the `@processing-role` attribute and select **OK**.

   ![](../../../../../.gitbook/assets/changing_processing-role_attribute_to_resource-only.png)

5. Repeat this process for all ditamaps within your bookmap that you want to exclude from the final publication.

