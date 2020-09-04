---
title: white balance
applicable-verison: 3.4
tags: 
working-color-space: not-applicable (RAW) 
view: darkroom
masking: false
---

Set the white balance of the image by (a) altering the temperature and tint, (b) defining a value of each (RGB) channel, or \(c\) choosing from list of predefined white balances.

The default settings for this module are derived from the image's Exif data.

## Module Controls

### scene illuminant temp

In this section there are scene illuminanant temperature and tint controls which set the white balace of the image. Click on 'scene illuminant temp' to cycle between 3 different slider color modes.

temperature
: Set the color temperature in Kelvin.

tint
: Alter the color tint of the image, from magenta (value `< 1`) to green (value `> 1`)

### white balance presets

setting
: Choose from a predetermined list of white balances. The available selections are dervied from the presets available on the camera that was used to take the photograph. The following options are provided in addition to the camera-defined white balance presets.

: **as shot** (default): The white balance as reported by the camera

: **from image area**: Draw a rectangle over a neutral color in the image from which the white balance will be automatically calculated

: **user modifed**: Most recently modified setting. Adjusting temperature, tint or r/g/b channel coefficients will set any chosen setting to this option. Choosing this setting after trying any other preset will return values to their most recently modified state

: **camera reference**: Set the temperate to camera reference white point, which is assumed to be D65 (or ~6502K). The white balance channel multipliers are calculated so that the pure white in the camera colorspace is converted into pure white in sRGB D65 (where pure white means that each color channel has an equal value). 

: For convenience the final four modes can also be set by clicking on one of the buttons above the **_setting_** drop-down.

finetune
: Finetune specific white balance preset from camera. Only shown if available. Direction of adjustment is dependent on provided presets. If your camera doesn't have white balance presets available, check https://github.com/darktable-org/darktable/wiki/White-balance-presets to see how you can submit your own.

### channel coefficients

By default the RGB channel coefficients are hidden. Expand/collapse the channel coefficients section by clicking on either the 'channel coefficients' header or the adjacent "arrow" button.

red/green/blue
: Set the value of each RGB channel from `0` to `8`

## Module reference

### colored sliders

### button bar

### additional options

