---
title: tone mapping
applicable-verison: 3.2.1
tags: 
working-color-space: RGB 
view: darkroom
masking: true
---

Compress the tonal range of HDR images, so they fit into the limits of a normal, low dynamic range image, using Durand's 2002 algorithm. 

The underlying algorithm uses a bilateral filter to decompose an image into a coarse base layer and a detail layer. The contrast of the base layer is compressed, while the detail layer is preserved, then both layers are re-combined.

## Module Controls

contrast compression
: The contrast compression level of the base layer. A higher compression will make the image fit a lower dynamic range.

spatial extent
: The spatial extent of the bilateral filter. Lower values cause the contrast compression to have stronger effects on image details.