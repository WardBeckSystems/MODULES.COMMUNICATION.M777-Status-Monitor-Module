# M777 · Communication

Ward-Beck Systems M777. Wiki page: [M777 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M777.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 0 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 6 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 0 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 0 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 0 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 0 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 1 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 2 |

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1vvcLhBmFpO-nU_twcgbw6Xr5GQ-KRgs5/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1vvcLhBmFpO-nU_twcgbw6Xr5GQ-KRgs5" width="240" alt="19xx - M777 - DOC - 777-03-005 - EINISH PAINT GREX TEXCOTE VINYL.jpg"></a><br><sub>19xx - M777 - DOC - 777-03-005 - EINISH PAINT GREX TEXCOTE VINYL</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1dYU4QZzHguPZdHOv3vXrx9dQrK3QtSJm/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1dYU4QZzHguPZdHOv3vXrx9dQrK3QtSJm" width="240" alt="19xx - M777 - DOC - 777-03-009 - REMOVE BURRS SHARP EDGES.jpg"></a><br><sub>19xx - M777 - DOC - 777-03-009 - REMOVE BURRS SHARP EDGES</sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M777.stl`](MECHANICAL/M777.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M777)

- **Size:** 41 × 178 mm panel, 165 mm deep, 3.2 mm plate (assumed: 1.6" x 7" x 6.5", the common module)
- **From the drawing:** 0 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M777 - front panel.svg`)
- no drawing of the front panel: the panel is blank
- Made by `tools/module_models.py` (→ `MECHANICAL/M777.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [M777.kicad_sym](KICAD/M777.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
