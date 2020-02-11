---
layout: default
title: Auto Folding/Unfolding
nav_order: 4
---

# Auto Folding/Unfolding
In order to improve SQL readability, MinBatis auto folds SQL statement in Java annotation when it loses focus
and a SQL statement is unfolded when it get focused again to make it easy for editing.
```Focus``` here means that the caret is placed on a SQL statement.

![folding](/assets/images/auto-folding-unfolding/folding.png){:class="screenshot"}

Auto-unfolding is made 500ms delayed when a SQL statement get focused in order to avoid unexpected unfolding when we move caret by keyboard narrows quickly.

Let's see what it looks like:

<script src="https://fast.wistia.com/embed/medias/3t8zjejn0q.jsonp" async></script><script src="https://fast.wistia.com/assets/external/E-v1.js" async></script><div class="wistia_responsive_padding" style="padding:72.81% 0 0 0;position:relative;"><div class="wistia_responsive_wrapper" style="height:100%;left:0;position:absolute;top:0;width:100%;"><div class="wistia_embed wistia_async_3t8zjejn0q videoFoam=true" style="height:100%;position:relative;width:100%"><div class="wistia_swatch" style="height:100%;left:0;opacity:0;overflow:hidden;position:absolute;top:0;transition:opacity 200ms;width:100%;"><img src="https://fast.wistia.com/embed/medias/3t8zjejn0q/swatch" style="filter:blur(5px);height:100%;object-fit:contain;width:100%;" alt="" aria-hidden="true" onload="this.parentNode.style.opacity=1;" /></div></div></div></div>
