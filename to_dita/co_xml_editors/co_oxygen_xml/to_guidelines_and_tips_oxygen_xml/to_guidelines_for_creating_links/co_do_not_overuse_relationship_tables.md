---
authorinformation:
  - null
  - Kimberley.De.Moor
category: User Guide
keyword: null
---

# Do not overuse relationship tables

Relationship tables are useful in linking content that does not get connected by the hierarchical linking system. Still, it is important not to start linking too much. What applies for inline linking, applies for relationship tables as well. Too many will only confuse the user.

A good general rule to keep in mind is that hierarchical linking is nearly error-proof and low maintenance. As such, it is a good system to rely on. Only start adding relationship tables if you need relevant topics of information to be linked for the user’s convenience. When you do, follow these guidelines:

* Add links for sibling topics if you set the `@linking` attribute to none in the parent topic but want to have related links for a select few of the child topics.
* Add links between topics that would not otherwise be there in the hierarchy of links.
* Add links to topics outside of the hierarchy in the current DITA map.
* Keep the number of related links in each topic to fewer than five when possible.

