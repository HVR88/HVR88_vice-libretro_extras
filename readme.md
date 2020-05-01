# VICE Libretro - Border Cropping (BC) Edition - Pixelpiper 2020

## The goal of this vice-libretro fork:

To provide options to fit/fill any monitor of any aspect ratio, size or resolution, with perfectly scaled, non-distorted emulator screens at each platform’s correct aspect ratio - the resulting output should closely match the proportions/dimensions originally seen on a CRT/TV.

Output and features must work with all displays/monitors: 16:9, 16:10, 5:4, 4:3, LCDs, CRTs, etc. at any desktop resolution - including portrait-rotated modes/displays. All computer displays should be outputting native/1:1 PAR modes to replicate original Commodore Aspect Ratios generated by this core.

All new features/options must integrate with original Core Options UI look/feel/methods and function correctly with other existing features/options.

Code kept clean and to format/style of existing project, making merging to original master branch as straight-forward as possible.

## Features ##
* Quick Zoom/Border Cropping presets
  * Small, Medium and Full border cropping - both width & height
  * Fit to Narrow & Fit to Wide (screens) - width or height
  * Custom cropping - displays additional options below
  
* Separate Horizontal & Vertical cropping options for C64, C128, Vic-20 and Plus4 cores
  * Preset-based with 3 crop settings for Horizontal & 4 for Vertical, including complete border removal
  * Supports PAL & NTSC for every platform with appropriately-selected cropping presets for both Horizontal and Vertical
  * No buggy side-effects of the Display Border Off option

* Manual Vertical Cropping Option for C64 and C128 cores - make the output perfectly fit any game
  * Independent Top and Vertical Cropping settings from 0 to 60 pixels (NTSC cropping restricted to match PAL range)
  * With support for over-cropping beyond the border to work with widest-possible range of games/titles

* Hot Key to toggle (ON/OFF) the currently set cropping for both Horizontal and Vertical at the same time

* Hot Key to cycle through the Quick Zoom / Border Cropping presets

* Hot Key to cycle through the presets for Horizontal Cropping

* Hot Key to cycle through the presets for Vertical Cropping - includes Manual Crop setting


## Screenshot of Core Options ##

![Screenshot](https://github.com/HVR88/Project_Screenshots/blob/master/vice-libretro-cropping_small.png?raw=true)


Requirements: **Retroarch settings: Video settings -> Scaling -> Aspect Ratio: Core Provided + Integer Scaling: OFF**

***
The new options have been adopted by the emulation community and a large collection of games have been profiled to provide the optimal crop values to work on any display in the *C64 Dreams Curated Collection:* https://forums.launchbox-app.com/topic/49324-c64-dreams-massive-curated-c64-collection

**What others have said**

*”now 100% of the cropping is handled in the core itself, [RetroArch] video settings are untouched. This is a godsend because now it should “just work” for everyone. Equally important is that now that I can adjust these crops by single pixels, they’re more exact than the previous pre-defined zoom levels.”*

*”I’ll be honest, I wish every core had this option. I would use it. At the very least Beetle PSX and Beetle Saturn could really use it.Thank you for doing this! It resolves probably the single biggest issue with this project, so that’s a major boon.”*

