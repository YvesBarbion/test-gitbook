---
authorinformation:
  - null
  - Pieterjan.vandenwegh
keyword: null
---

# Print button is not visible on smaller screen

## Condition

The print button is by default shown on the webhelp responsive on larger screen. However, on smaller devices the button disappears.

## Cause

The Bootstrap template is made in such a way that the button is invisible.

## Remedy

1. Open the custom CSS file.
2. Add the following CSS code

   ```text
   wh_print_link {
   display: inline-block !important;
   }
   ```

