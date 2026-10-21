# ScopedBlowguns

Lets you zoom in on your targets with a proper sniper scope when using the blowgun. Smooth aiming transitions, three adjustable zoom levels, and mouse sensitivity that adjusts to your zoom. The blowgun keeps its normal firing behavior!

## Showcase 1
![Mod Showcase Blowgun GIF](https://raw.githubusercontent.com/Rombuszz/PEAK-ScopedBlowguns/main/SHOWCASE-FILES/blowguns-mod-with.gif)

## Showcase 2
| Zoom Level | Pictures |
| :---: | :---: |
| `Vanilla` | ![Mod Showcase Blowgun Vanilla](https://raw.githubusercontent.com/Rombuszz/PEAK-ScopedBlowguns/main/SHOWCASE-FILES/blowguns-mod-zoomlevel-zero.png) |
| `Level 1` | ![Mod Showcase Blowgun Level 1](https://raw.githubusercontent.com/Rombuszz/PEAK-ScopedBlowguns/main/SHOWCASE-FILES/blowguns-mod-zoomlevel-one.png) |
| `Level 2` | ![Mod Showcase Blowgun Level 2](https://raw.githubusercontent.com/Rombuszz/PEAK-ScopedBlowguns/main/SHOWCASE-FILES/blowguns-mod-zoomlevel-two.png) |
| `Level 3` | ![Mod Showcase Blowgun Level 3](https://raw.githubusercontent.com/Rombuszz/PEAK-ScopedBlowguns/main/SHOWCASE-FILES/blowguns-mod-zoomlevel-three.png) |

## Usage - Basics

Hold a blowgun in your hands, then hold `RMB` to aim through the scope. Release `RMB` anytime to smoothly return to your normal view.

While scoped in, use `MouseWheelUp` to increase zoom, or `MouseWheelDown` to decrease it.<br>
Your selected zoom level is remembered between uses during the current session.

## Usage - Advanced

### [SETTINGS - Preset]

This setting allows you to switch between 3 preset scope styles.<br>
Select which scope style to use by setting this value to `1`, `2`, or `3`.<br>

***For now, only the first preset is available. Later on I might add the other two if I feel like it, or enough people request it.***<br>

In the meantime, you can add your own presets. Name the scope pictures you want to use, as `scope-2`, or `scope-3`, and place them into the root folder of the mod. Have fun :)

### [SETTINGS - Zoom Levels]

Each zoom level has an adjustable field of view. Smaller values mean stronger zoom.<br>
All three settings accept values from `15` to `60` degrees.

The mod automatically orders your configured values from weakest to strongest zoom, so scrolling up always moves toward the stronger zoom level, and scrolling down always moves toward the weakest zoom level.<br>

Mouse sensitivity adjusts automatically as the view zooms in or out.

## Config

**The mod supports scope selection and adjustable zoom levels through the bepinex config.**

SETTINGS: Preset:
- *DEFAULT VALUE*: `1`
- *ACCEPTABLE VALUES*: `1/2/3`

SETTINGS: ZoomLevel One FOV:
- *DEFAULT VALUE*: `40`
- *ACCEPTABLE VALUES*: `15-60`

SETTINGS: ZoomLevel Two FOV:
- *DEFAULT VALUE*: `25`
- *ACCEPTABLE VALUES*: `15-60`

SETTINGS: ZoomLevel Three FOV:
- *DEFAULT VALUE*: `15`
- *ACCEPTABLE VALUES*: `15-60`

![Bepinex Config Settings Page](https://raw.githubusercontent.com/Rombuszz/PEAK-ScopedBlowguns/main/SHOWCASE-FILES/UI-bepinex-config.png)

## Bug Reports/Questions/Support

https://rombusz.dev/contacts/bug-report/
