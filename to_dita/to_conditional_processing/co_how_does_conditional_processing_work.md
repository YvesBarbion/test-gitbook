---
authorinformation:
  - null
  - Kimberley.De.Moor
category: User Guide
keyword: null
---

# Using DITAVAL files in DITA

Conditional processing means you apply attribute values to certain elements of your text. These values are then entered into a separate DITAVAL \(DITA values\) file in which you write rules that specify whether elements with those values need to be included, excluded \(filtering\) or flagged \(highlighting\). While generating output, the rules in this DITAVAL file are applied to the end-result.

Below, the three main steps in conditional processing are described.

## Planning an attribute scheme

Before worrying about applying conditions, you should first establish a scheme and define exactly what you need to create conditions for. This way you can plan out which attributes you need and which values to assign to each of them. To do this, define your:

1. Audience: who will use your product and what specific information do they need?
2. Platform: which operating systems, platforms and other environments are used with your product?
3. Product: which models/versions are you planning and how do they differ?

**Attention:**

Each of the items you define should receive a unique value in an attribute. Do not re-use value names in different attributes as this will lead to confusion for your writers.

You want to teach your users how to save their files using Microsoft Word, but you know there are several version of Word on the market. As your documents only deal with Word 2003 and Word 2007, you plan your conditional attributes and values accordingly:

| Purpose | Attribute | Value |
| :--- | :--- | :--- |
| Only for Word 2003 | `@platform` | 2003 |
| Only for Word 2007 | `@platform` | 2007 |

## Applying attributes

Once you have specified which values you need and in which circumstances you will need them, you can start applying them as you write. Applying them while writing is far easier than having to hunt through your documentation afterwards to find the elements that are product-, audience- or platform-specific.

You can apply conditional attribute values in:

| Element | Purpose |
| :--- | :--- |
| Topics | Include, exclude or flag specific elements |
| DITA maps | Include or exclude entire topics |

**Note:** It is recommended to apply attributes to the topic references in the DITA map, and not to the `topic` element within the topic in question.

**Related information**

