# 3D printing guide (v20)

Print `cad/v20-final/pen_v20_flap_PRINT.step` as one piece. A ready sliced file for the Bambu Lab H2D is in [`print/h2d_pen_big_flap.gcode.3mf`](../print/h2d_pen_big_flap.gcode.3mf).

## Settings (Bambu Studio, H2D / H2S, 0.4 mm nozzle)

| Setting | Value |
| --- | --- |
| Material | PETG (bends far better than PLA at 0.45 mm) |
| Plate | Textured PEI or Engineering plate (glue stick on smooth PEI) |
| Layer height | 0.12-0.16 mm |
| Supports | Off |
| Detect thin wall | On (the flap is 0.45 mm, one line wide) |
| Wall generator | Arachne |
| Elephant foot compensation | 0.15 mm |
| Brim | Painted brim under the flap base only, about 3 mm |
| Outer wall speed | About 60 mm/s, or Silent mode, so the tall thin flap is not knocked |

## Check before printing

In the slicer preview, drag the layer slider through the flap and check that:
- The flap is one continuous line on every layer.
- Both flap holes are open on the first layer.
- The protrusion heads on the left side build up layer by layer.

## After printing

1. Bend the flap round the nose a few times to loosen the fold.
2. Writing: push the lock hole over the rear protrusion until it clicks under the head.
3. Closed: move the lock hole to the front protrusion. The flap bows into an arch over the nib.
