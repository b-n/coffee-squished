# Coffee-Squished

A coffee WDT tool built using FreeCAD 1.0.

- `./Fancy` contains the fancy version which requires the Curves Workbench.
- `./NoCurves` contains the version without the fancy cutout, and just needs vanilla FreeCAD.

Inspiration from many spirograph WDT tools, but I wanted to make one as compact as possible,
without the need for any extra parts.

FreeCAD docs are full constrained with adjustable parameters.

## BOM

- Filament
- 1x 6813 bearing. 85mm OD, 65mm ID, 10mm height
- 8x MR63ZZ ball bearings. 6mm OD, 3mm ID, 2.5mm height
- 4x M3x12mm screws (could probably get away with 10mm, but I had 12mm on hand)
- 10x accupuncture needles. Handle is 1.4mm thick. I used 0.35mm, but 0.25mm might be better for
  more flex on the needles.
- Some epoxy

Assembly:

1. Print all the things (I used 40% infill, "transparent" PLA)
1. Find a way to cut down the needles. My needles did not like having their handle shortened, thus
   the epoxy. There is probably a better way to do this, but this is what I did...
1. Assemble all the things.

Note:

- Most things are press fix. This includes the small bearings. You may want to tighten the bearings
  together with a bolt and nut first to aid it in if your tolerances are too tight.
- Do not poke you eyes out. Needles are sharp. Cut the needles down to fit
