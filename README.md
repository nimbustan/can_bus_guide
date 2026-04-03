# CAN Bus Technical Guide

**Comprehensive Technical Reference and Application Guide**\
Controller Area Network Protocols, Implementation, and Diagnostics

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/Content-CC%20BY--NC--SA%204.0-blue.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![License: Apache 2.0](https://img.shields.io/badge/Code-Apache%202.0-orange.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![Pages](https://img.shields.io/badge/Pages-152-green.svg)](#)
[![Chapters](https://img.shields.io/badge/Chapters-17-green.svg)](#)
[![Diagrams](https://img.shields.io/badge/Diagrams-66-green.svg)](#)

> A bilingual (English / Turkish) technical guide covering CAN 2.0, CAN FD, CAN XL, SAE J1939, CANopen, UDS, OBD-II, EMC testing, harness design, DBC file format, and CAN data logging & analysis — with 66 diagrams, real-world examples, and ISO standard references.

**Website:** [nimbustan.github.io/can_bus_guide](https://nimbustan.github.io/can_bus_guide/)

## Available Editions

| Edition | Language | Description          | Website                                               | PDF                                                                                     |
|---------|----------|----------------------|-------------------------------------------------------|-----------------------------------------------------------------------------------------|
| **EN**  | English  | Full English edition | [Open](https://nimbustan.github.io/can_bus_guide/en/) | [Download](https://nimbustan.github.io/can_bus_guide/en/can_bus_technical_guide_en.pdf) |
| **TR**  | Türkçe   | Full Turkish edition | [Aç](https://nimbustan.github.io/can_bus_guide/tr/)   | [İndir](https://nimbustan.github.io/can_bus_guide/tr/can_bus_technical_guide_tr.pdf)    |

## Topics Covered

- **CAN 2.0A/B** — Physical layer, data link layer, frame formats, bit timing
- **CAN FD & CAN XL** — Extended payloads, higher data rates, migration
- **SAE J1939** — 29-bit IDs, PGN structure, transport protocol, diagnostics
- **CANopen** — NMT, SDO, PDO, Object Dictionary, EDS/DCF
- **OBD-II & UDS** — ISO 14229, OBDonUDS, WWH-OBD, security access
- **EMC & Harness** — ISO 11452, ISO 7637, cable routing, shielding
- **DBC Files** — Syntax, signal decoding, byte order, multiplexing
- **Troubleshooting** — Common faults, diagnostic tools, field procedures

## Repository Structure

```
can_bus_guide/
├── en/                              # English website + PDF
│   ├── index.html
│   ├── can_bus_images/
│   └── can_bus_technical_guide_en.pdf
├── tr/                              # Turkish website + PDF
│   ├── index.html
│   ├── can_bus_images/
│   └── can_bus_technical_guide_tr.pdf
├── index.html                       # Language selector (redirects to en/)
└── README.md                        # ← You are here
```

## Project Stats

| Metric                       | Value            |
|------------------------------|------------------|
| Chapters                     | 17 + Appendix    |
| Pages                        | 152 per edition  |
| Diagrams & Figures           | 66               |
| Tables                       | 90               |
| ISO/SAE Standards Referenced | 30+              |
| Languages                    | English, Turkish |

## License

| Content                                | License                                                               |
|----------------------------------------|-----------------------------------------------------------------------|
| Guide content (text, diagrams, layout) | [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) |
| Code examples                          | [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)     |

**Guide content (CC BY-NC-SA 4.0):** You may share and adapt with attribution, but not for commercial purposes, and derivative works must be shared under the same license.

**Code examples (Apache 2.0):** You may copy, modify, and freely use in your own projects (including commercial); however, you must retain the original copyright notice.

## Author

**Murat Mecit KAHRAMANLI**

- GitHub: [@nimbustan](https://github.com/nimbustan)
- Project: [nimbustan.github.io/can_bus_guide](https://nimbustan.github.io/can_bus_guide/)

---

© 2026 Murat Mecit KAHRAMANLI. All rights reserved.
