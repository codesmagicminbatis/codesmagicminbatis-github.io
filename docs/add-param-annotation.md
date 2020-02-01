---
layout: default
title: Add @Param Annotation
nav_order: 15
---

# Add @Param Annotation
MinBatis provides an intention action to add @Param to method parameter more convenient.
MinBatis automatically adds prefix to existing parameter in SQL statement when adding @Param annotation.
This is also a very useful feature when we do refactor (e.g., add more parameter to the mapper method, etc.).

![add param](/assets/images/add-param-annotation/add-param.gif)