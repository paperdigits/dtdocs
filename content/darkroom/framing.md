---
title: framing
applicable-verison: 3.2.1
tags: 
working-color-space: RGB 
view: darkroom
masking: true
---

Generate a frame around the image. The frame consists of a border with a user defined color and a frame line inside that border, with a second user defined color. There are various options to control the geometry of the frame.

## Module Controls

border size
: The size of the frame as a percentage of the underlying full image.

aspect
: The aspect ratio of the final module output (i.e. of the underlying image plus the frame)

orientation
: The orientation of the frame (portrait/landscape). Choose 'auto' for darktable to select the most reasonable orientation based on the underlying image.

horizontal/vertical position
: Select from a set of pre-defined ratios where you want your underlying image be positioned on the horizontal/vertical axis. You can also right click and enter your own ratio as “x/y”.

frame line size
: The percentage of the frame line size relative to the border size at its smallest part.

frame line offset
: Where the frame line is positioned, relative to the underlying image. Choose 0% for a frame line touching the image. Choose 100% for a frame line touching the outer border limits.

border color / frame line color
: A pair of color selectors which allow the border and frame line colors to be defined. Clicking on the colored field will open a color selector dialog which offers a choice of commonly used colors, or allows you to define a color in RGB color space.

: You can also activate a color picker to take a color probe from the image.