---
layout: default
title: OGNL Support
nav_order: 14
---

# OGNL Support
MyBatis uses OGNL to support dynamic SQL which is very powerful.
You can find more details about OGNL at [Dynamic SQL](http://www.mybatis.org/mybatis-3/dynamic-sql.html).

You can use it with following elements in dynamic SQL:
* if
* when
* bind
* dynamic parameter

MinBatis integrates OGNL to support auto-completion, inspections, navigation, refactoring, etc.

![ognl](/assets/images/ognl-support/ognl.png)

# OGNL Identifier
Our previous **MyBatis plugin** can't parse OGNL identifier well which causes some features (e.g., identifier chain, find usage, rename refactor, etc.) are missing.
MinBatis parses OGNL identifier the right way which provides the missing features.

![better](/assets/images/ognl-support/better.png)