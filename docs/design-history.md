# Design history

How ZEITLOS went from a three-part model to the final one-piece pen. Physical tests from the process documentation come first, then the CAD iterations. Full sheets: [ZEITLOS_process_sheets.pdf](ZEITLOS_process_sheets.pdf).

## Physical exploration

| Step | What was tested | Outcome |
| --- | --- | --- |
| Paper model | Faceted prism with a chamfered tip; two halves hinging from one end; laid flat as two channels joined at a fold | Proportion, faceted section and end-hinge opening chosen |
| Living-hinge tests | Three printed hinges: short span, long span, edge hinge | Hinge chosen for the pen |
| Gap and refill test | Printed tip section with a refill in place | Refill on the pen axis, nib out at the tip; gap between halves checked |
| Iteration 01 | First snap-fit print, two separate parts | Failed: snap dimensions too far off, halves did not engage |
| Iteration 02 | Corrected snap-fit | Halves close and hold |
| Iteration 03 | Small flap and nib-cap test prints | Values carried into the full model |

## CAD iterations

| Version | Change |
| --- | --- |
| Base | 2.2 mm walls, snaps, joining plate. Internal refill dimensions frozen from here on |
| Early | Back wall moved to the narrow half (B). Snaps redistributed rear, centre and tip, with flex slits in half A. 0.8 mm joining plate |
| Clip and cap | Integrated S-shaped pocket clip near the rear. A fold-over tip cap was tried, then removed |
| v5 | 0.10 mm tip gap between the halves, rear alignment bump and dimple, rounded nose |
| v6-v7 | Sliding hood and separate sliding flap explored; rejected in favour of one attached flap |
| v8 | Simple flap attached to the pen: one round nib hole, one rectangular lock hole, two protrusions on top |
| v9 | Protrusions raised to bed level for printing |
| v10 | Support-free nose fill and channel; flap root blended into the body. Printed: bridges still needed support |
| v11 | Mechanism moved to the sides. Flap printed standing upright from the right side of the nose, teardrop holes, wedge protrusions |
| v12-v13 | Bigger lock on the top-flap variant, refill moved forward. The 1 mm channel bridge printed badly, so the side flap was kept |
| v14 | Side flap: bigger lock (0.25 mm clearance), refill 1.5 mm forward, single lock hole |
| v15 | Small locking lip added on the protrusions |
| v16 | Flap thinned 0.6 to 0.45 mm so it bends; barbed locking heads; larger nib slot |
| v17 | Taller locking heads; refill 2.0 mm forward; travel 11 mm |
| v18 | Hole positions re-placed for a curved (not sharp) fold at the flap joint |
| v19 | Nib hole fully enclosed by the flap |
| **v20 (final)** | Flap lengthened for a looser 1.8 mm fold; locking heads 1.75 mm above the flap with 0.40 mm overlap; clearance window so the flap lies flat over the front protrusion while writing; protrusions 5.5 and 15.0 mm behind the face; travel 9.5 mm |

## Lessons carried forward

- Holes printed flat shrink from first-layer squish. Allow 0.20-0.25 mm per side, or use elephant-foot compensation.
- A 0.6 mm printed flap is too stiff to fold. 0.45 mm (one line width) bends.
- A free fold never bends sharply. Place holes for the real fold radius, and leave slack rather than come up short.
