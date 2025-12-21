# opi5-m2-sbc-enclosure

Open hardware enclosure for SBC boards compatible with the **Orange Pi 5 form factor**, designed using **FreeCAD**.

The project is intended to be flexible and reusable, allowing multiple use cases rather than being limited to a single purpose.

## Overview

This enclosure supports:

- SBC boards with **dimensions compatible with the Orange Pi 5**
- **M.2 slot for storage**
- **Two 3.5" HDDs**
- Dedicated space for a **power supply**
- Space for a **voltage regulator**
- Modular and parametric structure

It can be used for projects such as:
- Home server
- Homelab
- NAS
- Application server
- Other SBC-based use cases

## Tools

- **FreeCAD**: version **1.0.2 (stable)**

## Repository structure (suggested)

```
├─ model/ # Main FreeCAD file (.FCStd)
├─ exports/ # STEP, STL, DXF
├─ README.md
└─ LICENSE
```

## Design notes

- The model is **parametric**, allowing dimension adjustments
- Stable naming for sketches and features is recommended
- Structural changes should be made through the main parameters

## License

This project is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

You are free to use, modify, and redistribute this project, including for commercial purposes, **as long as proper credit is given to the original author**.

See the [LICENSE](LICENSE) file for more details.
