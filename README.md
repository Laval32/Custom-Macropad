# Custom Macropad

A custom 3×3 macropad built from scratch with a **XIAO RP2040**, custom PCB, and 3D-printed case.

<img width="1348" height="1026" alt="hackpad case" src="https://github.com/user-attachments/assets/5e50875c-18dd-45e8-be9a-63ec808a40eb" />


## Features

* 9 programmable keys
* EC11 rotary encoder with push button
* 0.91" OLED display
* Custom PCB designed in KiCad
* 3D-printed two-piece case
* QMK firmware
* DSA keycaps

## Design

### Schematic

<img width="1414" height="808" alt="hackpad schematic" src="https://github.com/user-attachments/assets/559fb2e1-05cd-49f3-b4f8-50b311146da6" />

### PCB

<img width="826" height="1072" alt="hackpad PCB" src="https://github.com/user-attachments/assets/74ebf97b-52f9-425e-a4cd-73d45c48fd9f" />

### Case

<img width="1348" height="1026" alt="hackpad case" src="https://github.com/user-attachments/assets/58b1f569-0d0a-4504-8280-cbb8677572f9" />


## BOM

| Quantity | Part                               |
| -------- | ---------------------------------- |
| 1        | XIAO RP2040                        |
| 9        | 1N4148 Diodes                      |
| 9        | Cherry MX Switches                 |
| 1        | EC11E Rotary Encoder (with switch) |
| 1        | 0.91" OLED Display                 |
| 9        | DSA Keycaps                        |
| 4        | M3×16mm Screws                     |
| 4        | M3×5mm×4mm Heatset Inserts         |
| 1        | 3D-Printed Case (Top + Bottom)     |

## Firmware

The macropad uses **QMK** for key mapping and rotary encoder functionality.
