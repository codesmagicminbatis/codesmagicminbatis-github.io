---
layout: default
title: Dynamic SQL Parsing
nav_order: 4
---

# MyBatis Plugin
There are two main issues that our previous *MyBatis Plugin* can't handle properly.

Let's see what's are these.

## Dynamic SQL in Annotation
*MyBatis Plugin* can't parse dynamic SQL in Java annotation which causes many unexpected errors like this:

![annotation dynamic sql](/assets/images/dynamic-sql-parsing/annotation-dynamic-sql.png){:class="screenshot"}

## Parse Dynamic SQL
*MyBatis Plugin* can't parse dynamic SQL which causes that some syntax errors are ignored.

![syntax error](/assets/images/dynamic-sql-parsing/syntax-error.png){:class="screenshot"}

# MinBatis
**MinBatis** can parse dynamic SQL well.

It trims/inserts appropriate tokens according to the semantic of dynamic tags (e.g. trim tag).

### Dynamic SQL in Annotation
**MinBatis** supports dynamic SQL in Java annotation.

![annotation dynamic sql](/assets/images/dynamic-sql-parsing/annotation-dynamic-sql-2.png){:class="screenshot"}

## Parse Dynamic SQL
**MinBatis** parses dynamic SQL properly.

![syntax error highlighting](/assets/images/dynamic-sql-parsing/syntax-error-highlighting.png){:class="screenshot"}

## Other Features
As we'll see that some other features are implemented based on the correctly parsed dynamic SQL.