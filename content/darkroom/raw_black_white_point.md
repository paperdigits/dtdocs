---
title: raw black/white point
applicable-verison: 3.2.1
tags: 
working-color-space: Not Applicable (RAW) 
view: darkroom
masking: false
---

This module is activated automatically for all raw images and defines camera-specific black and white points. Default settings are applied for all supported cameras. Changes to the defaults are normally not required.

## Module Controls

black level 0-3
: The camera-specific black level of the four pixels in the RGGB Bayer pattern. Pixels with values lower than the defined level are considered to contain no valid data.

white point
: The camera-specific white level. All pixels with values above this are likely to be clipped and will be handled accordingly in the _highlight reconstruction_ module.