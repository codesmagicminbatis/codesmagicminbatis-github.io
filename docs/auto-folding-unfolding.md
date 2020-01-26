---
layout: default
title: Auto Folding/Unfolding
nav_order: 4
---

# Auto Folding/Unfolding
In order to improve SQL readability, MinBatis auto folds SQL statement in Java annotation when it loses focus
and a SQL statement is unfolded when it get focused again to make it easy for editing.
```Focus``` here means that the caret is placed on a SQL statement.

![folding](/assets/images/auto-folding-unfolding/folding.png)

Auto-unfolding is made 500ms delayed when a SQL statement get focused in order to avoid unexpected unfolding when we move caret by keyboard narrows quickly.

Let's see what it looks like:

![folding](/assets/images/auto-folding-unfolding/folding.gif)
