---
authorinformation:
  - null
  - Pieterjan Vandenweghe
keyword: null
---

# Flow bv Schematron checks

At Flow bv, we currently use the following Schematron checks which are based the Structured Writing training and Microsoft Manual of Style:

* Language related checks:
  * abbrevations.sch
  * anthropomorphism.sch
* General convention checks:
  * filename\_conventions.sch
  * leading-trailing-space.sch
  * number-of-li.sch
  * list-endings.sch
  * starts-with-capital.sch
  * space-inline-elements.sch
* DITA related checks:
  * nested-elements.sch
  * fmdpi.sch

## abbrevations.sch

This rule checks the usage of the following abbreviations and makes a suggestion for a straightforward substitute:

| Abbreviation | Suggestion |
| :--- | :--- |
| i.e. | that is |
| viz. | namely |
| e.g. | for example |
| ergo | therefore |

## anthropomorphism.sch

Anthropomorphism is attributing human characteristics or behavior to things that are not human. The following words may be all right to use in the right context, but they often signal inappropriate anthropomorphism. Some are appropriate only for programmers or information technology professionals:

\|allow\|interested in\|recognize\| \|answer\|know\|refuse\| \|assume\|let\|remember\| \|aware\|like\|see\| \|behave\|own\|think\| \|decide\|permit\|understand\| \|demand\|realize\|want\|

## filename\_conventions.sch

This rule checks the usage of the correct prefix for each content type:

| content type | prefix |
| :--- | :--- |
| topic | to\_ |
| concept | co\_ |
| task | ta\_ |
| reference | re\_ |
| ditamap | \_ |
| troubleshooting | tr\_ |
| bookmap | \_\_ |
| glossary | gloss\_ |

## leading-trailing-space.sch

This rule checks leading and trailing spaces in a number of elements.

## number-of-li.sch

This rule checks the number of list items in an unordered and ordered list and the number of steps in a procedure based on Miller's law. Don't use &gt; 7 + 2 items in a list or procedure.

## list-endings.sch

This rule checks the end punctuation in a list item \(`li`\) and step \(`cmd`\). A list and a step can end on a colon and dot.

## starts-with-capital.sch

This rule checks the capitalization at the beginning of the following elements:

* `title`
* `li`

## space-inline-elements.sch

This rule checks the spacing right before and after the following inline elements:

* `menucascade`
* `uicontrol`
* `ph`
* `msgph`
* `msgnum`
* `term`
* `keyword`

## nested-elements.sch

This rule checks for the following nested elements in the `p` element and asks to move it outside the `p` element:

* `ul`
* `ol`
* `table`
* `note`
* `codeblock`
* `dl`
* `draft-comment`
* `fig`

## fmdpi.sch

This rules check if the `image` element has an `@outputclass` attribute value that start with fmdpi.

