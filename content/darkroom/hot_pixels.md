---
title: hot pixels
applicable-verison: 3.2.1
tags: 
working-color-space: Not Applicable (RAW) 
view: darkroom
masking: true
---

Automatically detect and eliminate hot pixels. Hot pixels are pixels which failed to record a light level correctly. Detected hot pixels are replaced by an average of their neighbors.

## Module Controls

threshold
: How strong a pixel's value needs to deviate from its neighbors to be regarded as a hotpixel.

strength
: The strength of blending hotpixels with their surrounding.

detect by 3 neighbours
: Extend the detection of hotpixels: regard a pixel as hot if a minimum of only three (instead of four) neighbor pixels deviate by more than the threshold level.

mark fixed pixels
: Visually mark the corrected pixels on the image and display a count of hot pixels that have been fixed