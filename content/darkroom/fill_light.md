---
title: fill light
applicable-verison: 3.2.1
tags: 
working-color-space: Lab 
view: darkroom
masking: false
---

Locally modify exposure based on pixel lightness.

This module pushes exposure by increasing lightness with a Gaussian curve of a specified width, centered on a given lightness.

## Module Controls

exposure
: The fill-light exposure (EV)

center
: The median lightness impacted by the fill-light. The lightness must be set manually but a color picker can be used to provide a guide. The lightness of the selected point/area is displayed in the gradient bar.

width
: The width of the Gaussian curve. This number is expressed in zones, with the full range being 10 zones.