# -12V-to-3V3-Buck-Convertor

## Description

My Altium project includes a schematic and layout design for a buck converter using the TPS54202H to step down from 12V to 3.3V with a 2A output capability.

## Schematic Drawings

### Schematic Drawing
![Screenshot 2024-08-12 020210](https://github.com/user-attachments/assets/2bf1fb27-fb2f-4ece-9151-b3459960d3eb)

### Layout
![Screenshot 2024-08-12 020309](https://github.com/user-attachments/assets/ef0e4b6c-cf05-46e1-9657-bc6bd0811d83)
![Screenshot 2024-08-12 020324](https://github.com/user-attachments/assets/5ed20ccb-6a81-40b5-b83a-7b91cb5b1963)

### Bill of materials(BOM)

| Comment  | Description                                        | Designator | Footprint            | LibRef                | Quantity |
|----------|----------------------------------------------------|------------|----------------------|-----------------------|----------|
| 10uF     | Multi-Layer Ceramic Capacitor 10uF 50V X5R±10% 1206 Emboss T/R | C1         | FP-GRT31C0_2-IPC_A   | CMP-06035-000076-2    | 1        |
| 0.1uF    | Capacitor                                          | C2, C3     | C0805                | C0805C104K6RACTU      | 2        |
| 22uF     | None                                               | C4, C5     | FP-1206-L_3_2_0_3-W_1_6_0-IPC_A | CMP-14477-000099-2 | 2        |
| 75pF     | CAPCER75PF50V NP0 1206                             | C6         | FP-C1206C-EB-MFG     | CMP-1037-01478-2      | 1        |
| TPS54202HDDCR | Integrated Circuit                            | IC1        | SOT95P280X110-6N     | TPS54202HDDCR         | 1        |
| 10uH     | Inductor                                           | L1         | SRN6045_1            | SRN6045-100M          | 1        |
| 510kΩ    | RES Thick Film, 510kΩ, 1%, 0.125W, 100ppm/°C, 0805 | R1         | FP-CRCW0805-e3-IPC_B | CMP-2001-03987-2      | 1        |
| 49.9kΩ   | RES Thick Film, 49.9kΩ, 1%, 0.125W, 100ppm/°C, 0805 | R2        | FP-CRCW0805-e3-IPC_C | CMP-2001-03952-2      | 1        |
| 100kΩ    | RES Thick Film, 100kΩ, 1%, 0.125W, 100ppm/°C, 0805 | R3         | FP-CRCW0805-e3-MFG   | CMP-2001-04899-2      | 1        |
| 22.1kΩ   | RES Thick Film, 22.1kΩ, 1%, 0.125W, 100ppm/°C, 0805 | R4        | FP-CRCW0805-e3-IPC_C | CMP-2001-03689-2      | 1        |

