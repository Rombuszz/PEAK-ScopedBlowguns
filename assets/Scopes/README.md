# Scope overlay

`scope-1-classic-v1.png` is the single current scope overlay: a transparent 1254 x 1254 RGBA PNG with a black center dot, four plain crosshair lines, and a simple circular rim. Generated with the built-in image generation tool using the former Classic and Mil-dot overlays as references.

Ship it in `Scopes/scope-1-classic-v1.png` beside the DLL. Previous artwork is archived under `artifacts/backups` and is not part of the release assets.

Keep the C# and three-preset config intact. To enable the other presets later, add `scope-2-mildot-v1.png` and `scope-3-digital-v1.png` to `Scopes` and restart PEAK. The current loader logs missing-image errors for absent presets but falls back to the available preset 1. No DLL changes are needed to add the future images.

Generation brief: combine the simple Classic outline and Mil-dot center aiming dot; opaque black center dot; exactly four straight, uniform black crosshair lines connecting to the dot; no bumps, extra dots, ticks, labels, colored illumination, or charge indicator; genuinely transparent aperture; centered circular inner radius approximately 44% of image width.
