# 3×3 Custom Macropad

A custom 3×3 macropad built from scratch with a **XIAO RP2040**, custom PCB, and 3D-printed case.

![Macropad](overall.png)

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

![Schematic](schematic.png)

### PCB

![PCB](pcb.png)

### Case

![Case](case.png)

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
