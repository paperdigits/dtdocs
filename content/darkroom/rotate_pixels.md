---
title: rotate pixels
applicable-verison: 3.2.1
tags: 
working-color-space: RGB 
view: darkroom
masking: false
---

The sensors of some cameras (such as the Fujifilm FinePix S2Pro, F700, and E550) have a diagonally oriented Bayer pattern instead of the usual orthogonal layout.

Without correction this would lead to a tilted image with black corners. This module applies the needed rotation.

_darktable_ detects images that need correction by their Exif data and automatically activates this module where required. For other images the module always remains disabled.

The module has no controls.