---
authorinformation:
  - null
  - Pieterjan.vandenwegh
keyword: null
---

# Layout Webhelp responsive is not OK in Edge

## Condition

The layout of the Webhelp responsive is not correct when opened in Microsoft Edge.

## Cause

Some info is lacking in the header of the HTML page.

## Remedy

1. Do one of the following:

   ```text
   |**There is no XHTML file available with custom header info.**|Create a new XHTML file.|
   ```

   \|**There is already an XHTML file available with custom header info.**\|Open the existing XHTML file\|

2. Add the following code: `<meta http-equiv="X-UA-Compatible" content="IE=edge" />`.

