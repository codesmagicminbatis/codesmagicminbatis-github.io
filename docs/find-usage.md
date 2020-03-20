---
layout: default
title: Find Usage
nav_order: 11
---

# Find Usage
When you write or edit code, you might come across a code element that you want to change or delete.
Before you make the changes, it is a good practice to see where the code element is used and how it affects the application.
With the Find Usages actions you can search for the references of your code element throughout the whole codebase.
You can find more about ```Find Usage``` at [Search for usages](https://www.jetbrains.com/help/idea/find-highlight-usages.html).

With MinBatis, you can find the usage of elements that may be potentially used by MyBatis framework.
You can also use ```Declaration or Usage``` action to find usages if the caret is placed at the declaration element.

## Attribute Value

![attribute value](/assets/images/find-usage/attribute-value.png){:class="screenshot"}

## Getter/Setter Method

![getter setter](/assets/images/find-usage/getter-setter.png){:class="screenshot"}

## Bean Field

![getter setter](/assets/images/find-usage/field.png){:class="screenshot"}

## Parameter

![parameter](/assets/images/find-usage/parameter.png){:class="screenshot"}

## @Param

![param annotation](/assets/images/find-usage/param-annotation.png){:class="screenshot"}

## Constructor Parameter

![constructor](/assets/images/find-usage/constructor.png){:class="screenshot"}

## Table Column

![table column](/assets/images/find-usage/table-column.png){:class="screenshot"}

# Mark Symbol as Used
Without MinBatis, some symbols will be marked as ```never used``` or ```never assigned``` by IntelliJ IDEA even if it's actually used by MyBatis framework.

![never used](/assets/images/find-usage/never-used.png){:class="screenshot"}

MinBatis can detect those symbols used by MyBatis framework and mark them as used, finally the highlighting is gone.
This also works for private members.

![used by MyBatis](/assets/images/find-usage/used-by-myBatis.png){:class="screenshot"}
