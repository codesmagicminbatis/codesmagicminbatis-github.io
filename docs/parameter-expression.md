---
layout: default
title: Parameter Expression
nav_order: 6
---

# Parameter Expression
Mybatis supports simple parameter expression in SQL statements.
Parameters can specify a more specific data type in SQL parameter with parameter expression.
You can find more details about parameter expression at [MyBatis Documentation](http://www.mybatis.org/mybatis-3/sqlmap-xml.html#Parameters) and [ParameterExpression](https://github.com/mybatis/mybatis-3/blob/master/src/main/java/org/apache/ibatis/builder/ParameterExpression.java)

# Builtin Support
The plugin integrates parameter expression as a custom language in IntelliJ.
It's context-aware and very useful.

![parameter expression](/assets/images/parameter-expression/parameter-expression.gif)

# Color Scheme
You can customize the color scheme for the custom language in settings.
Open the configuration dialog via ```Preferences/Settings -> Editor -> Color Scheme -> Min Marker```.

![color scheme](/assets/images/parameter-expression/color-scheme.png)
