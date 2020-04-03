---
layout: default
title: Known Issue
nav_order: 19
---

# Known Issue

## Escape In Java/Kotlin Annotation
A exception will be propagated if we escape special character in dynamic script

![escape in annotation](/assets/images/known-issue/escape-in-annotation.png){:class="screenshot"}

![escape exception](/assets/images/known-issue/escape-exception.png){:class="screenshot"}

There is a known issue in the IntelliJ platform, see [IDEA-225126](https://youtrack.jetbrains.com/issue/IDEA-225126) for more details.
We'll keep an eye on this and improve it as soon as it's fixed in the IntelliJ platform.
