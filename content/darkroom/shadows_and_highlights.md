---
title: shadows and highlights
applicable-verison: 3.2.1
tags: 
working-color-space: Lab 
view: darkroom
masking: true
---

Modify the tonal range of the shadows and highlights of an image by enhancing local contrast.

## Module Controls

shadows
: Control the effect on shadows. Positive values will lighten shadows while negative values will darken them.

highlights
: Control the effect on highlights. Negative values will darken highlights while positive values will lighten them.

white point adjustment
: By default the algorithm of this modules leaves the black and white points untouched. In some cases an image might contain tonal variations beyond the white point, i.e. above a luminance value of 100. A negative shift in the white point adjustment can bring these values down into the proper range so that further details in the highlights become visible.

soften with
: The underlying blurring filter: gaussian or bilateral. Try the bilateral filter if the gaussian blur generates halos.

radius
: The radius of the blurring filter used by the algorithm. Higher values give softer transitions between shadows and highlights but might introduce halos. Lower values will reduce the size of halos but may lead to an artificial look. The bilateral filter is much less prone to halo artifacts.

compress
: Control how strongly the effect extends to the midtones. High values limit the effect to only the extreme shadows and highlights; lower values also cause adjustments to the midtones. At 100% this module has no visible effect as only absolute black and absolute white are affected.

shadows color adjustment
: Controls the color saturation adjustment made to shadows. High values cause saturation enhancements on lightened shadows; low values cause desaturation on lightened shadows. It is normally safe to leave this at its default of 100%. This gives a natural saturation boost on shadows – similar to what you would expect in nature if shadows were to receive more light.

highlights color adjustment
: Control the color saturation adjustment made to highlights. High values cause saturation enhancements on darkened highlights; low values cause desaturation on darkened highlights. Often highlights do not contain enough color information to give convincing colors when darkened. You might need to adjust this parameter in order to find the best fitting value depending on your specific image, but be aware that sometimes the results might not be fully satisfying.
