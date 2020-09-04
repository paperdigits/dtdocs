---
title: denoise (bilateral filter)
applicable-verison: 3.2.1
tags: 
working-color-space: RGB 
view: darkroom
masking: true
---

Denoise high ISO images. 

This module reduces noise in the image while preserving sharp edges. This is accomplished by averaging pixels with their neighbors, taking into account not only the geometric distance but also the distance on the range scale (i.e. differences in the RGB values).  The module is particularly effective if one RGB channel is more noisy than the others. In such a case, use the _channel mixer_ module to examine the channels one by one, in order to set the blur intensities accordingly.

As denoising is a resource hungry process, it slows down pixelpipe processing significantly; consider activating this module late in your workflow.

## Module Controls

radius
: The spacial extent of the gaussian blur.

red, green, blue
: The blur intensity for each of the RGB channels.