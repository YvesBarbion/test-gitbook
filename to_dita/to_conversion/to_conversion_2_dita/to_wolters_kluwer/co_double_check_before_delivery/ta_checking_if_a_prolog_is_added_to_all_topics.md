---
authorinformation:
  - null
  - null
category: null
keyword: null
---

# Checking if a prolog is added to all topics

1. Open the Xpath/Xquery Builderwindow in OxygenXML.
2. Choose the correct **Scope:**.
3. Search for `node()[not(ancestor-or-self::map)]/title [not(following::prolog)]`.
4. Choose the **Execute Xpath:** icon.

   You get an overview all topics without prolog.

5. Add the correct prolog where needed.

