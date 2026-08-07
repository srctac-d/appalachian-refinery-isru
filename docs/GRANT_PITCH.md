# ⚡ EPCS Grant Pitch: Circular Coal Ash Refinery & Infrastructure

## Executive Summary
The Electrochemical Power and Cooling System (EPCS) provides a dual-solution pathway for coal-impacted regions:
1. **Critical Mineral Extraction:** Processes 600 TPD of coal ash (CCR) to recover 99.9% Scandium Oxide and battery-grade Vanadium Pentoxide ($V_2O_5$).
2. **Geocrete Waste Conversion:** Converts 100% of residual ash into 6,000 PSI Geocrete for underground Utilidor infrastructure, eliminating hazardous surface ash ponds.
3. **Data Center Decarbonization:** Uses recovered Vanadium in a closed-loop "Electronic Blood" VRFB system to deliver direct DC power and liquid thermal management to AI server racks.

## Alignment Targets
* **DOE Critical Minerals Accelerator (Topic Area 3):** Characterization and recovery of REEs/Critical Minerals from unconventional coal feedstocks.
* **WVDEP AMLER Program:** Economic development and brownfield-to-battery transformation in the Parkersburg/WV corridor.

2. Simple Flow Diagram or ASCII Map in docs/ARCHITECTURE.md

Visuals help readers understand how the liquid loops work together. You can add a dedicated architecture overview:

2. Simple Flow Diagram or ASCII Map in docs/ARCHITECTURE.md

Visuals help readers understand how the liquid loops work together. You can add a dedicated architecture overview:
Markdown

# 🏗️ EPCS Physical & Thermal Architecture

                  +-----------------------------+
                  | 600 TPD Coal Ash Feedstock  |
                  +--------------+--------------+
                                 |
                                 v
                  +-----------------------------+
                  |  Alkali / Leaching Process  |
                  +------+---------------+------+
                         |               |
          +--------------+               +--------------+
          | (Residue)                                   | (Extract)
          v                                             v

+--------------------+                        +--------------------+
| 6,000 PSI Geocrete |                        | Vanadium Electrolyte|
+----------+---------+                        +----------+---------+
|                                             |
v                                             v
+--------------------+                        +--------------------+
| Underground        |====== (Encases) ======>| 4-Pipe Utilidor    |
| Utilidor Shell     |                        | Liquid Distribution|
+--------------------+                        +----------+---------+
|
v
+--------------------+
| Rack Cabinet       |
| DC Power & Cooling |
+--------------------+
3. CONTRIBUTING.md


*Note: All contributions are subject to the project's open license.*
