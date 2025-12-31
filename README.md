# Orange Pi 5 Enclosure

Open hardware enclosure for SBC boards compatible with the **Orange Pi 5 form factor**, designed using **FreeCAD**.

The project is intended to be flexible and reusable, allowing multiple use cases rather than being limited to a single purpose.

## Overview

This enclosure supports:

- SBC boards with **dimensions compatible with the Orange Pi 5 Ultra**
- **M.2 slot for storage atapter**
- **Two 3.5" regular HDDs**
- Dedicated space for a **power supply**
- Space for a **voltage regulator**
- Modular and parametric structure

It can be used for projects such as:
- Home server
- Homelab
- NAS
- Application server
- Other SBC-based use cases

## Compatible Components

The components listed below are **mechanically and electrically compatible** with the enclosure design.

> **Note:**  
> Only **one power supply** and **one voltage regulator** are required.  
> Multiple options are listed to provide alternative compatible parts.

| Category          | Qt  | Component                                | Notes                                                                       | Link                                              |
| ----------------- | --- | ---------------------------------------- | --------------------------------------------------------------------------- | ------------------------------------------------- |
| Power Supply      | 001 | 12V Power Supply (EPP-120S-12)           | Choose **one** compatible power supply as the main power input              | https://aliexpress.com/item/1005007384009922.html |
| Power Supply      |   - | 12V 6A Power Supply (alternative)        | Alternative compatible power supply                                         | https://aliexpress.com/item/1005007292767666.html |
| Voltage Regulator | 001 | 5V 10A DC Voltage Regulator              | Choose **one** compatible regulator to step down from 12V to 5V for the SBC | https://aliexpress.com/item/1005007384626696.html |
| Voltage Regulator |   - | 5V 9A DC Voltage Regulator (alternative) | Alternative compatible voltage regulator                                    | https://aliexpress.com/item/1005008520047850.html |
| Storage Adapter   | 001 | M.2 to Dual SATA Adapter                 | Enables connection of two SATA drives via M.2 (style1 or style 3)           | https://aliexpress.com/item/1005004426464683.html |
| Power Connector   | 001 | Molex Connector for HDD                  | Power connector for 3.5″ HDDs                                               | https://aliexpress.com/item/1005004831094459.html |
| USB Connector     | 001 | 90-degree USB Connector                  | Angled USB connector to fit enclosure layout                                | https://aliexpress.com/item/1005009712372737.html |
| Switch            | 001 | Standard Switch                          | Button KCD11-101                                                            | https://aliexpress.com/item/1005004124751042.html |
| Screw             | 020 | M3 x 5mm thread shoulder screw           | -                                                                           | https://pt.aliexpress.com/item/4001072025844.html |
| Storage           | 002 | 3.5″ HDD                                 | Standard 3.5″ SATA hard drives are compatible (compatible with 1 HDD)       | Any standard 3.5″ SATA HDD                        |

## Design tools

- **FreeCAD**: version **1.0.2 (stable)**

## Repository structure

```
├─ model/   # Main FreeCAD file (.FCStd)
├─ exports/ # STL Files
├─ fonts/   # Used fonts (opensource)
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
