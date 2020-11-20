---
authorinformation:
  - null
  - Pieterjan Vandenweghe
keyword:
  - Schematron
  - Schematron QuickFix
---

# Validation of your style guide

As a technical writer, you follow company business rules that are defined in a style guide. With the style guide you aim at consistently written documentation. The rules in the style guide can vary a lot, for example:

* Start a title with a capital.
* Never use more than x words in a title.
* Don't use too many list items in a list or procedure.
* Avoid an attribute in an element.
* Require an attribute value in an element.
* Add the correct metadata.

It's not simple to keep track of all of the rules and sometimes you simply forget one of them. As an occasional writer or SME it's even more difficult to keep track of all these rules. That's why it comes in handy to get reminders when you forget or make a mistake against one of the rules.

You can create this kind of reminders with the help of Schematron and even suggest possible fixes with Schematron QuickFix. In a kind of way you create an instant revisor.

## About Schematron

Schematron is a language using assertions about the presence or absence of a pattern in an XML document and can be used amongst other for quality control and quality assurance purposes.[1](./#fntarg_1)

## About Schematron QuickFix

Schematron QuickFix is an extension of Schematron and provides a possible solution for a problem found with a Schematron rule. With just one click you remove the problem that was found with a Schematron rule and change it into correct text.[2](./#fntarg_2)

## Workflow

1. Someone \(for instance, an Information Architect\) writes business rules in a style guide.
2. An XML-specialist turns the business rule into a Schematron pattern.
3. This Schematron pattern can be used to automatically detect instances in which a technical writer has not adhered to \(one of\) the predefined business rules. The technical writer can then quickly find excerpts that don’t match the business rules and instantly correct them by clicking on the light bulb that appears before the problem in question.

**Related information**

[1](./#fnsrc_1) [http://schematron.com/](http://schematron.com/)[2](./#fnsrc_2) [http://www.schematron-quickfix.com/](http://www.schematron-quickfix.com/)

