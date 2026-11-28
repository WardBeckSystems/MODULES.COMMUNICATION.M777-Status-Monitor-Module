# M777 Status Monitor Module · Communication

Ward-Beck Systems M777, 1982|15. Wiki page: [M777 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M777.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 8 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 15 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 3 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 5 |

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1vvcLhBmFpO-nU_twcgbw6Xr5GQ-KRgs5/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1vvcLhBmFpO-nU_twcgbw6Xr5GQ-KRgs5" width="240" alt="19xx - M777 - DOC - 777-03-005 - EINISH PAINT GREX TEXCOTE VINYL.jpg"></a><br><sub>19xx - M777 - DOC - 777-03-005 - EINISH PAINT GREX TEXCOTE VINYL · <a href="MECHANICAL/19xx%20-%20M777%20-%20DOC%20-%20777-03-005%20-%20EINISH%20PAINT%20GREX%20TEXCOTE%20VINYL%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1dYU4QZzHguPZdHOv3vXrx9dQrK3QtSJm/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1dYU4QZzHguPZdHOv3vXrx9dQrK3QtSJm" width="240" alt="19xx - M777 - DOC - 777-03-009 - REMOVE BURRS SHARP EDGES.jpg"></a><br><sub>19xx - M777 - DOC - 777-03-009 - REMOVE BURRS SHARP EDGES · <a href="MECHANICAL/19xx%20-%20M777%20-%20DOC%20-%20777-03-009%20-%20REMOVE%20BURRS%20SHARP%20EDGES%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M777.stl`](MECHANICAL/M777.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M777)

- **Size:** 41 × 178 mm panel, 165 mm deep, 3.2 mm plate (assumed: 1.6" x 7" x 6.5", the common module)
- **From the drawing:** 0 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M777 - front panel.svg`)
- no drawing of the front panel: the panel is blank
- Made by `tools/module_models.py` (→ `MECHANICAL/M777.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [19xx - 777-01-002 - M777A STATUS MONITOR MODULE FUNCTIONAL - ISS 1.kicad_sch](KICAD/19xx%20-%20777-01-002%20-%20M777A%20STATUS%20MONITOR%20MODULE%20FUNCTIONAL%20-%20ISS%201.kicad_sch)
- [19xx - 777-02-002 - M777A STATUS MONITOR MODULE SCHEMATIC - ISS 1.kicad_sch](KICAD/19xx%20-%20777-02-002%20-%20M777A%20STATUS%20MONITOR%20MODULE%20SCHEMATIC%20-%20ISS%201.kicad_sch)
- [M777.kicad_sym](KICAD/M777.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
