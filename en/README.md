# CAN Bus Technical Guide — English Edition

**Comprehensive Technical Reference and Application Guide**\
Controller Area Network Protocols, Implementation, and Diagnostics

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/Content-CC%20BY--NC--SA%204.0-blue.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![License: Apache 2.0](https://img.shields.io/badge/Code-Apache%202.0-orange.svg)](https://www.apache.org/licenses/LICENSE-2.0)

> **152 pages** · **17 chapters** · **66 diagrams** · **90 tables** · **30+ ISO/SAE standards**

**Website:** [nimbustan.github.io/can_bus_guide/en/](https://nimbustan.github.io/can_bus_guide/en/index.html)\
**PDF Download:** [can_bus_technical_guide_en.pdf](https://nimbustan.github.io/can_bus_guide/en/can_bus_technical_guide_en.pdf)\
**Turkish Edition:** [nimbustan.github.io/can_bus_guide/tr/](https://nimbustan.github.io/can_bus_guide/tr/can_bus_technical_guide_tr.pdf)

---

## About

This guide is a comprehensive, single-document technical reference for CAN Bus technology. It is designed for automotive engineers, embedded systems developers, test engineers, and anyone working with CAN-based communication networks. The guide covers the full CAN ecosystem — from physical layer signaling to application-layer protocols, diagnostics, EMC testing, and file formats.

All content is based on official ISO, SAE, and CiA specifications with real-world implementation examples, signal-level diagrams, and practical troubleshooting procedures.

## Table of Contents

### Part I — CAN Fundamentals (Chapters 1–5)

| Chapter | Title                                | Page  |
|---------|--------------------------------------|-------|
|  **1**  | Introduction to CAN Bus              |    6  |
|   1.1   | History and Evolution                |    6  |
|   1.2   | OSI Model Mapping                    |    7  |
|   1.3   | CAN Standards Overview               |    8  |
|  **2**  | Physical Layer (ISO 11898-2)         |    9  |
|   2.1   | Differential Signaling               |    9  |
|   2.2   | Bus Termination                      |   10  |
|   2.3   | Transceiver Characteristics          |   11  |
|  **3**  | Data Link Layer                      |   13  |
|   3.1   | Frame Formats                        |   13  |
|   3.2   | Bit Timing                           |   15  |
|   3.3   | Synchronization                      |   16  |
|  **4**  | Error Handling                       |   17  |
|   4.1   | Error Types                          |   17  |
|   4.2   | TEC and REC Counters                 |   18  |
|   4.3   | Bus States                           |   19  |
|   4.4   | Fault Confinement & Bus-Off Recovery |   20  |
|  **5**  | Network Topology                     |   23  |
|   5.1   | Bus Wiring                           |   23  |
|   5.2   | Stub Lengths                         |   24  |
|   5.3   | Cable Specifications                 |   24  |

### Part II — SAE J1939 (Chapters 6–8)

| Chapter | Title                                          | Page  |
|---------|------------------------------------------------|-------|
|  **6**  | SAE J1939 Protocol Stack                       |   26  |
|   6.1   | 29-bit Identifier Structure                    |   26  |
|   6.2   | PGN Structure                                  |   27  |
|   6.3   | Address Claiming                               |   30  |
|   6.4   | Physical Layer and Connector Specifications    |   32  |
|   6.5   | J1939 Document Structure and Related Standards |   34  |
|   6.6   | J1939 Request Mechanism                        |   36  |
|   6.7   | Identification Requests                        |   37  |
|  **7**  | J1939 Transport Protocol                       |   40  |
|   7.1   | TP.CM and TP.DT                                |   40  |
|   7.2   | BAM Protocol                                   |   41  |
|   7.3   | Multi-packet Messages                          |   42  |
|  **8**  | J1939 Diagnostics                              |   45  |
|   8.1   | DTC Structure                                  |   45  |
|   8.2   | SPN-FMI-OC-CM                                  |   45  |
|   8.3   | DM Messages                                    |   47  |

### Part III — Automotive Diagnostics (Chapters 9–10)

| Chapter | Title                                                | Page  |
|---------|------------------------------------------------------|-------|
|  **9**  | Automotive Diagnostics — OBD-II and UDS              |   48  |
|   9.1   | OBD-II Protocol                                      |   48  |
|   9.2   | UDS Protocol                                         |   50  |
|   9.3   | Protocol Comparison                                  |   57  |
|   9.4   | Diagnostic Protocol Standards — OSI Layer Mapping    |   59  |
|   9.5   | OBDonUDS and WWH-OBD — Diagnostic Protocol Evolution |   60  |
|   9.6   | OBD-II Messaging Scenarios                           |   62  |
|   9.7   | J1939 OBD-II Diagnostics (Extended 29-bit IDs)       |   65  |
|   9.8   | UDS Messaging Scenarios                              |   67  |
|   9.9   | UDS Services                                         |   73  |
|  9.10   | Session Control                                      |   74  |
|  9.11   | Security Access                                      |   75  |
| **10**  | CAN FD and CAN XL Evolution                          |   77  |
|  10.1   | CAN FD Features                                      |   77  |
|  10.2   | CAN XL Features                                      |   79  |
|  10.3   | Migration Considerations                             |   82  |

### Part IV — Implementation & Testing (Chapters 11–13)

| Chapter | Title                          | Page  |
|---------|--------------------------------|-------|
| **11**  | EMC Testing and Harness Design |   83  |
|  11.1   | ISO 11452 Testing              |   83  |
|  11.2   | ISO 7637 Transients            |   85  |
|  11.3   | Harness Design Guidelines      |   86  |
| **12**  | Practical Implementation       |   94  |
|  12.1   | System Architecture            |   94  |
|  12.2   | Bus Loading Analysis           |   95  |
|  12.3   | Gateway Design                 |   96  |
| **13**  | Troubleshooting                |   98  |
|  13.1   | Common Faults                  |   98  |
|  13.2   | Diagnostic Tools               |   99  |
|  13.3   | Field Debug Procedure          |  102  |
|  13.4   | Best Practices                 |  105  |

### Part V — Advanced Topics (Chapters 14–17)

| Chapter | Title                                    | Page  |
|---------|------------------------------------------|-------|
| **14**  | J1939 with CAN FD                        |  106  |
|  14.1   | Multi-PG and Contained PGs               |  106  |
|  14.2   | CAN FD Transport Protocol                |  108  |
|  14.3   | Network Management and Functional Safety |  110  |
|  14.4   | J1939-76 Functional Safety Communication |  112  |
| **15**  | CANopen Protocol                         |  115  |
|  15.1   | Architecture and Communication Objects   |  118  |
|  15.2   | SDO and PDO Services                     |  120  |
|  15.3   | Object Dictionary, EDS and DCF           |  122  |
| **16**  | CAN DBC File Format                      |  126  |
|  16.1   | DBC Syntax and Structure                 |  126  |
|  16.2   | Signal Decoding                          |  128  |
|  16.3   | Advanced DBC Features                    |  129  |
| **17**  | CAN Bus Data Logging & Analysis          |  131  |
|  17.1   | Introduction to CAN Data Logging         |  131  |
|  17.2   | CAN Log File Formats                     |  133  |
|  17.3   | ASAM MDF Standard                        |  136  |
|  17.4   | CAN Logging Hardware                     |  138  |
|  17.5   | Analysis Software & Python Ecosystem     |  141  |
|  17.6   | Practical Analysis with Python           |  144  |
|  17.7   | Format Conversion Workflows              |  147  |
|         | **Appendix A: Reference Tables**         |  150  |
|         | **References**                           |  152  |

## Key Topics in Detail

### CAN Physical Layer
- Differential signaling (CAN_H / CAN_L), dominant/recessive states
- Bus termination: 120Ω placement, split termination, AC termination
- Transceiver specifications (TJA1050, MCP2551, ISO 11898-2 compliance)
- Signal integrity: propagation delay, common-mode rejection, ESD protection

### CAN Data Link Layer
- Standard (11-bit) and Extended (29-bit) frame formats
- Bit stuffing, CRC-15/CRC-17/CRC-21 calculations
- Bit timing: Sync_Seg, Prop_Seg, Phase_Seg1, Phase_Seg2, SJW
- Arbitration: non-destructive bitwise arbitration mechanism

### Error Handling
- Five error types: bit, stuff, CRC, form, ACK errors
- TEC/REC counters and state transitions
- Error-Active → Error-Passive → Bus-Off state machine
- Bus-Off recovery: automatic vs. controlled restart strategies

### SAE J1939
- 29-bit ID structure: priority, PGN, source address
- PGN encoding: PDU Format, PDU Specific, Data Page
- Address claiming (ISO 11783-5): NAME structure, contention resolution
- Deutsch 9-pin/DT06/HD10 connector pinouts
- J1939-21 Transport Protocol: RTS/CTS, BAM, timeout parameters
- Diagnostic Messages: DM1–DM50+, SPN-FMI fault code structure

### OBD-II & UDS Diagnostics
- OBD-II: ISO 15765-4, functional/physical addressing, Mode/PID structure
- UDS (ISO 14229): 26 services, session management, security access
- OBDonUDS (SAE J1979-2) and WWH-OBD (ISO 27145) evolution timelines
- Protocol stack comparison: OBD-II vs UDS vs J1939
- NRC (Negative Response Code) reference: 38 codes with descriptions

### CAN FD & CAN XL
- CAN FD: flexible data rate, up to 64-byte payload, BRS/ESI fields
- CAN XL: up to 2048-byte payload, SDU Type, priority-based arbitration
- SIC (Signal Improvement Capability) transceivers
- Migration considerations: hardware, software, network design

### EMC Testing & Harness Design
- ISO 11452 radiated immunity test methods
- ISO 7637 transient pulse testing (Pulse 1–5)
- Cable types: UTP, STP, double-shielded twisted pair
- Routing rules: separation distances, bend radii, connector selection
- Shield grounding strategies: single-point vs. multi-point

### CANopen
- NMT state machine: Initialization → Pre-operational → Operational → Stopped
- SDO transfer modes: Expedited, Segmented, Block
- PDO communication: event-driven, timer-driven, SYNC-driven
- Object Dictionary structure: index ranges, EDS/DCF file formats
- EMCY, SYNC, TIME, Heartbeat protocol objects

### CAN DBC File Format
- Message (BO_) and signal (SG_) syntax
- Signal decoding: raw → physical value conversion formula
- Byte order: Intel (little-endian) vs Motorola (big-endian)
- Signal multiplexing, attributes, value descriptions
- DBC tool ecosystem: Vector CANdb++, SavvyCAN, python-can

## Diagrams and Figures

The guide includes 66 custom-generated technical diagrams:

- CAN frame structure diagrams (Standard, Extended, CAN FD, CAN XL)
- Bus topology and termination schematics
- J1939 29-bit ID bitfield breakdowns
- Transport Protocol sequence diagrams (RTS/CTS, BAM)
- OBD-II and UDS message flow scenarios
- EMC test setup illustrations
- Connector pinout drawings (Deutsch 9-pin, M12, OBD-II)
- Protocol stack comparison charts
- Error state machine diagrams
- Cable cross-section and side-cutaway views

## Standards Referenced

| Standard         | Title                                       |
|------------------|---------------------------------------------|
| ISO 11898-1:2015 | CAN Data Link Layer and Physical Signalling |
| ISO 11898-2:2016 | CAN High-Speed Physical Layer               |
| ISO 15765-2      | ISO-TP Transport Protocol                   |
| ISO 15765-4      | OBD-II on CAN                               |
| ISO 14229        | UDS — Unified Diagnostic Services           |
| ISO 27145        | WWH-OBD                                     |
| SAE J1939-21     | J1939 Transport Protocol                    |
| SAE J1939-71     | Vehicle Application Layer                   |
| SAE J1939-73     | J1939 Diagnostics                           |
| SAE J1939-76     | Functional Safety Communication             |
| SAE J1979-2      | OBDonUDS                                    |
| CiA 301          | CANopen Application Layer                   |
| CiA 611          | CAN XL Data Link Layer                      |
| ISO 11452        | EMC — Radiated Immunity                     |
| ISO 7637         | EMC — Electrical Transients                 |

## How to Use

### Online Reading
Visit [nimbustan.github.io/can_bus_guide/en/](https://nimbustan.github.io/can_bus_guide/en/) for the interactive web version with navigation sidebar, clickable table of contents, and responsive layout.

### PDF Download
Download the [PDF version](https://nimbustan.github.io/can_bus_guide/en/can_bus_technical_guide_en.pdf) (152 pages) for offline reading, printing, or annotation.

### Turkish Edition
The complete guide is also available in Turkish at [nimbustan.github.io/can_bus_guide/tr/](https://nimbustan.github.io/can_bus_guide/tr/).

## License

| Content                                         | License                                                               |
|-------------------------------------------------|-----------------------------------------------------------------------|
| Guide content (text, diagrams, tables, layout)  | [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) |
| Code examples (CAN initialization, DBC parsing) | [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)     |

**Guide content (CC BY-NC-SA 4.0):**
- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material
- **Attribution** — you must give appropriate credit and indicate if changes were made
- **NonCommercial** — you may not use the material for commercial purposes
- **ShareAlike** — derivative works must be distributed under the same license

**Code examples (Apache 2.0):**
- You may copy, modify, and freely use in your own projects (including commercial)
- You must retain the original copyright notice and indicate changes made

## Disclaimer

This guide is prepared for educational purposes. The author makes no guarantees regarding the accuracy or completeness of the information. Code examples are simplified for teaching and are not recommended for direct use in production. The author shall not be held liable for any damages arising from the use of this guide.

ISO 11898, ISO 14229, SAE J1939, and CAN in Automation (CiA) specifications were used as references. All trademarks belong to their respective owners.

## Author

**Murat Mecit KAHRAMANLI**

- GitHub: [@nimbustan](https://github.com/nimbustan)
- Project: [nimbustan.github.io/can_bus_guide](https://nimbustan.github.io/can_bus_guide/)

---

First Edition: April 2026 — Version 1.0

© 2026 Murat Mecit KAHRAMANLI. All rights reserved.
