---
layout: default
title: Parameter Expression
nav_order: 8
---

# Parameter Expression
Mybatis supports simple parameter expression in SQL statements.
Parameters can specify a more specific data type in SQL parameter with parameter expression.
You can find more details about parameter expression at [MyBatis Documentation](http://www.mybatis.org/mybatis-3/sqlmap-xml.html#Parameters) and [ParameterExpression](https://github.com/mybatis/mybatis-3/blob/master/src/main/java/org/apache/ibatis/builder/ParameterExpression.java)

# Builtin Support
The plugin integrates parameter expression as a custom language in IntelliJ.
It's context-aware and very useful.

<div class="realtime">
    <script src="https://fast.wistia.com/embed/medias/vixfrg5e38.jsonp" async></script><script src="https://fast.wistia.com/assets/external/E-v1.js" async></script><div class="wistia_responsive_padding" style="padding:75.0% 0 0 0;position:relative;"><div class="wistia_responsive_wrapper" style="height:100%;left:0;position:absolute;top:0;width:100%;"><div class="wistia_embed wistia_async_vixfrg5e38 videoFoam=true" style="height:100%;position:relative;width:100%"><div class="wistia_swatch" style="height:100%;left:0;opacity:0;overflow:hidden;position:absolute;top:0;transition:opacity 200ms;width:100%;"><img src="https://fast.wistia.com/embed/medias/vixfrg5e38/swatch" style="filter:blur(5px);height:100%;object-fit:contain;width:100%;" alt="" aria-hidden="true" onload="this.parentNode.style.opacity=1;" /></div></div></div></div>
</div>

# Color Scheme
You can customize the color scheme for the custom language in settings.
Open the configuration dialog via ```Preferences/Settings -> Editor -> Color Scheme -> Min Marker```.

![color scheme](/assets/images/parameter-expression/color-scheme.png){:class="screenshot"}
