# 🗝️ Ajani’s Free Reproductible Picks Kit (AFRPK)

A catalog of reproducible pick geometries for research, prototyping, CTF training and professional use.  
Source files are provided as **FreeCAD** documents; SVG exports and preview images are produced from those sources.

---

## Identifier format

```
AFRPK #X.Y.Z[-W]
```

- `AFRPK` — Ajani's Free Reproductible Pick Kit  
- `X` — Pick form (examples):  
  - `H` = Hook  
  - `D` = Diamond  
  - `R` = Rake  
  - `S` = Snake  
  - (add more letters for other forms)  
- `Y` — Revision (start at `0`)  
- `Z` — Size variant (`1`, `2`, …; larger → visually larger pick)  
- `-W` — optional form variation (e.g. `-2`)

**Examples**
- `AFRPK #H.0.1` → Hook, rev 0, size 1  
- `AFRPK #R.1.3-2` → Rake, rev 1, size 3, variant 2

---

## Materials & manufacturing (reference only)

- **Material (nominal):** XC75 steel  
- **Thickness (nominal):** 0.50 mm  
- **Intended production processes:** EDM and CNC  

> Files are geometry-focused; no process parameters are included.

---

## File formats provided

- **FreeCAD (FCStd)** — editable source (primary)  
- **STEP** — geometry exchange for CAD workflows  
- **SVG** — 2D vector exports (generated from FreeCAD)  
- **PNG/JPEG** — rendered previews

---

## Contribution guidelines (summary)

1. Fork → branch `feat/<id-or-description>` → PR.  
2. Add FreeCAD source file and include a generated preview.  
3. Name files following the `AFRPK #X.Y.Z[-W]` convention.  
4. Keep changes focused on geometry and documentation; do not add process-specific parameters.  
5. Include a one-line description for each new model in your PR.

---

## Examples (naming)

- `AFRPK #H.0.1` — Hook, revision 0, size 1  
- `AFRPK #D.0.2` — Diamond, revision 0, size 2  
- `AFRPK #S.1.1-2` — Snake, revision 1, size 1, variant 2

---

## License

This work is licensed under **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**.  
Use and remix allowed for non-commercial purposes with attribution; derivative works must be shared under the same license.

