# PlayLight for gangQin

Custom piano light design.

---

## Overview

- **Type:** Amplifier
- **Domain:** Analog
- **Status:** Work in progress



---

## Features
TODO



---

## Interfaces

### Inputs
| Name | Type | Range | Description |
|-----|------|-------|-------------|
| IN | Audio | ±1V | Input signal |
| AMP_CV | Analog | 0–5 V | Volume control |

### Outputs
| Name | Type | Description |
|------|------|-------------|
| OUT | Audio | Filtered signal |

---

## Controls

| Control | Type | Description |
|--------|------|-------------|
| Cutoff | Potentiometer | Manual cutoff frequency |
| Resonance | Potentiometer | Feedback amount |

---

## Electrical Characteristics

- **Supply voltage:** ±12V
- **Current consumption:** TBD mA
- **Signal levels:** TBD

---

## Implementation Notes
Section is TODO.


---

## Files

| File | Description |
|-----|-------------|
| `headphones_amp_rev_A.pdf` | Electrical schematic (PDF export)|
| `headphones_amp_rev_A.kicad_pcb` | Schematic (KiCad 9.0.6)|
| `headphones_amp_rev_A.kicad_pcb` | PCB layout (KiCad 9.0.6)|
| `sim/XXX.asc` | SPICE simulation of the Schmitt Trigger |

---

## Calibration / Tuning
None.

---

## Known Issues / TODO
None.

---

## Revision History

| Revision | Date | Notes |
|--------|------|-------|
| Rev A | 2026-04-25 | Initial prototype without MCU |
| Rev B | YYYY-MM-DD | TBD |

---

## Tools
Designed with KiCAD 9.0.7

Designed on a 0.25mm grid (dimensions are driven by standard piano keyboard dimensions, which are in mm)
LED nets routed on a 0.20mm grid to avoid clearance issues when connecting to the LP5036.


---

## Related Modules

Links to other submodules in the repository:
- `../vca/`
- `../ring_modulator/`

---

## References
- TI datasheet: LP5036






