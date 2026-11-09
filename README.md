# keyboardV2: compact 61-key keyboard

A fully custom 61-key mechanical keyboard designed by me, including the PCB, case, firmware, and assembly.

Started With the Macondo Program and Finished with the Forge Program

## Features

- Custom PCB designed from scratch
- Hot-swappable MX-compatible switches
- ZMK firmware
- Screw-in stabilizers
- 3D printed two-piece tray mount case
- Switch plate
- PCB foam
- bluetooth
- RGB lights
  
## Why I Built It

I built another keyboard before this and ended up hating how it looked and how I desgined it. So I went back to the drawing board and decided to make one I would actually like.


## Design Process

The project began by selecting a 61-key layout that has a lot of function but is also on the smaller side. I then designed the PCB in KiCad, routed all the traces, and added support for hot-swap sockets and USB-C connectivity. After the electronics were complete I designed a simple tray mount in Onshape. The case is made out of two PLA printed pieces and includes a shelf for the pcb to rest on. Because of small bed size I will have to print them in pieces.

Finally, the keyboard will be flashed with VIA firmware



## Challenges

Some of the biggest challenges included:

- Learning PCB routing and keyboard matrix design
- Designing a printable case that was able to support the pcb well
- Ensuring all mounting points aligned correctly

## Images and Renders!

### Matrix Schematic
<img width="1280" height="754" alt="Screenshot 2026-07-24 220902" src="https://github.com/user-attachments/assets/bbcec30d-22e3-4f54-ae42-53581c906ddc" />

### OnShape Render
- assembly file is public at: https://cad.onshape.com/documents/9cbec0f54e40138e58fcc79a/w/808f2acb50a46c5c63af6f12/e/cd5daac02ca5b9e828f3d085

#### Case
<img width="1401" height="845" alt="image" src="https://github.com/user-attachments/assets/0df9c01a-283b-4ed9-98ff-5a62c992e601" />

### Switch Plate
<img width="1394" height="652" alt="image" src="https://github.com/user-attachments/assets/f2cf452c-596d-438e-a078-ca66a1b56f73" />


### PCB
<img width="1599" height="589" alt="image" src="https://github.com/user-attachments/assets/9d47d23c-50db-463c-bd9c-821cc94eaaa6" />


### Assembly
<img width="1453" height="778" alt="image" src="https://github.com/user-attachments/assets/b20cf742-f34f-4446-9993-de6c50083e28" />
<img width="1341" height="604" alt="image" src="https://github.com/user-attachments/assets/89bf1ebf-ddeb-4e28-b1af-81720d56bd0d" />



## Bill of Materials (BOM)

The following table lists the components required to build the custom 60% wireless mechanical keyboard.

| # | Component | Description | Quantity | Unit Price | Subtotal |
|---:|---|---|---:|---:|---:|
| 1 | [Glorious Fox Linear Switches](https://www.amazon.com/GLORIOUS-Linear-Mechanical-Switches-Keyboards/dp/B0D7QW8SQ9) | MX-compatible linear switches, 110-pack | 110 | $0.2272 | $24.99 |
| 2 | [Gateron PCB-Mounted Stabilizers](https://www.amazon.com/gp/product/B0BZYK3X1S) | PCB-mounted stabilizer set for larger keys | 1 set | $9.99 | $9.99 |
| 3 | [SuperMini nRF52840](https://www.amazon.com/AITRIP-Development-Bluetooth-Management-Module%EF%BC%8CNano/dp/B0DCZJKYL1) | Pro Micro alternative; Bluetooth LE and ZMK compatible | 1 | $13.99 | $13.99 |
| 4 | [SK6812MINI-E RGB LEDs](https://www.amazon.com/100PCS-Similar-WS2812B-Individually-Addressable/dp/B0DMNBBM9V) | Individually addressable per-key RGB LEDs, 100-pack | 100 | $0.15 | $15.46 |
| 5 | [Kailh Hot-Swap Sockets](https://www.amazon.com/Hot-swappable-Socket-CPG151101S11-Mechanical-Keyboard/dp/B096WZ6TJ5) | MX-compatible hot-swap sockets, 100-pack | 100 | $0.125 | $12.50 |
| 6 | [JLCPCB PCB Fabrication](https://jlcpcb.com) | Custom PCB manufacturing, 5 boards, including shipping | 1 order | — | $35.03 |
| 7 | [3.7V LiPo Battery](https://www.amazon.com/YTKavq-Battery-Lithium-Rechargeable-Connector/dp/B08TV4J9H7) | Rechargeable lithium polymer battery, approximately 1000mAh, JST-PH connector | 1 | $7.59 | $7.59 |
| 8 | [JST-PH 2.0mm Connector](https://www.amazon.com/JST-PH-Connector-Silicone-Cables-Female/dp/B0F9PD2LPW) | 2-pin battery connector with silicone wiring | 1 | $5.99 | $5.99 |
| 9 | [SPDT Slide Switch](https://www.amazon.com/gp/product/B0DN67RV4W) | Power on/off switch, 2.54mm pin spacing | 1 | $6.99 | $6.99 |
| 10 | [Momentary Tactile Push Button](https://www.amazon.com/Momentary-Tactile-Switches-Through-Breadboard/dp/B0G5Q9RPJW) | Reset button | 1 | $5.99 | $5.99 |
| 11 | [Womier Double-Shot PBT Keycaps](https://www.amazon.com/Keycaps-Doubleshot-Percent-Mechanical-Keyboard/dp/B0DDC6PNY6) | Cherry-profile double-shot PBT keycap set | 1 set | $17.99 | $17.99 |
| 12 | [22µF 0805 MLCC Capacitors](https://www.amazon.com/Chip-Capacitor-MLCC-22uF-CS2012X5R226M250NRE/dp/B096WDCLWY) | X5R ceramic capacitors for power filtering, 10-pack | 10 | $0.499 | $4.99 |
| 13 | [CHANZON 100nF 0805 Capacitors](https://www.amazon.com/CHANZON-100nF-Ceramic-Capacitor-100pcs/dp/B0GWH4RRQS) | LED decoupling capacitors, 100-pack | 100 | $0.076 | $7.60 |

### Cost Summary

| Category | Cost |
|---|---:|
| Components and hardware | $134.07 |
| PCB fabrication and shipping | $35.03 |
| **Total Project Cost** | **$169.10** |

*Prices are based on the listed purchase prices and may change. The PCB cost includes manufacturing and shipping.*

### Project Notes
- Keyboard layout: 60% ANSI.
- Connectivity: Bluetooth Low Energy (BLE).
- Firmware: ZMK.
- Switch compatibility: Cherry MX-style mechanical switches.
- Switch mounting: MX hot-swap sockets.
- Lighting: Individually addressable per-key RGB using SK6812MINI-E LEDs.
- Battery: Rechargeable 3.7V lithium polymer cell.
- Layers: Two firmware layers, with Right Alt configured as the Fn key.

## Shoutout hackclub and the macondo program

</center>
