# 555 LED Chaser PCB

![3D Render of PCB](images/3d_render.png)

---

## What is this?

This is a **555 LED Chaser** — a PCB that blinks 10 LEDs in a looping pattern.

I made this project to learn the basics of PCB design and by following the guided tutorial on the BluePrint website. I still have a lot to learn but this was a good start to learning how to use some of the tools.

---
## PCB

![PCB Layout](images/pcb_layout.png)

The board was designed in **KiCad**. It is a 2-layer PCB kept under 100×100mm. The outline is in the shape of Appa from Avatar the Last Airbender, a show that I love with all my heart.

---

## Schematic / Wiring Diagram

![Schematic](images/schematic.png)


## Bill of Materials (BOM)

| # | Component | Value / Part | Qty | Link |
|---|-----------|-------------|-----|------|
| 1 | 555 Timer IC | [NE555P](https://www.digikey.com/en/products/detail/texas-instruments/NE555P/277735) | 1 | [DigiKey](https://www.digikey.com/en/products/detail/texas-instruments/NE555P/277735) |
| 2 | Decade Counter IC | [CD4017BE](https://www.digikey.com/en/products/detail/texas-instruments/CD4017BE/67073) | 1 | [DigiKey](https://www.digikey.com/en/products/detail/texas-instruments/CD4017BE/67073) |
| 3 | Resistor | 1kΩ | 2 | [DigiKey](https://www.digikey.com/en/products/detail/yageo/CFR-25JB-52-1K/338) |
| 4 | Resistor | 470Ω | 1 | [DigiKey](https://www.digikey.com/en/products/detail/yageo/CFR-25JB-52-470R/343) |
| 5 | Potentiometer | 100kΩ | 1 | [DigiKey](https://www.digikey.com/en/products/detail/bourns-inc/3386P-1-104LF/1088979) |
| 6 | Electrolytic Capacitor | 10µF | 1 | [DigiKey](https://www.digikey.com/en/products/detail/panasonic-electronic-components/ECA-1HM100/245067) |
| 7 | Ceramic Capacitor | 0.01µF | 1 | [DigiKey](https://www.digikey.com/en/products/detail/kemet/C320C103K5R5TA/818254) |
| 8 | LEDs (assorted colors) | 5mm through-hole | 10 | [DigiKey](https://www.digikey.com/en/products/detail/kingbright/WP7113ID/1747663) |
| 9 | Pin Header (power) | 1×2 | 2 | [DigiKey](https://www.digikey.com/en/products/detail/adam-tech/PH2-02-UA/9830344) |
| 10 | PCB | Custom, 2-layer | 1 | [JLCPCB](https://jlcpcb.com) |

---

## Repository Structure

```
555-chaser/
├── README.md
├── bom.csv
├── images/
│   ├── 3d_render.png
│   ├── pcb_layout.png
│   └── schematic.png
├── kicad/
│   ├── 555-chaser.kicad_pro
│   ├── 555-chaser.kicad_sch
│   ├── 555-chaser.kicad_pcb
│   └── gerbers/
│       └── gerbers.zip
```

---
