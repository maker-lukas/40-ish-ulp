# 40%ish ulp

> A split wireless 36 key keyboard powered by the Seeed XIAO Nrf52840 with cherry ULP switches.

<div>
  <a target="_blank" href="https://kicanvas.org/?github=https%3A%2F%2Fgithub.com%2Fmaker-lukas%2F40-ish-ulp%2Fblob%2Fmain%2Fpcb%2Fulp.kicad_pro">
    <img src="assets/kicanvas_banner.png" alt="View on KiCanvas" width="95">
  </a>
</div>

<div>
  <a target="_blank" href="https://autode.sk/3Qic5Ux">
    <img src="assets/cad_banner.png" alt="View CAD" width="95">
  </a>
</div>

<div align="center">
  <img src="assets/banner.png" width="50%" style="transform: translateY(-50px);">
</div>

---

**40%ish** ulp is a split, ultra low profile keyboard with a 36 key layout, which is great when you are traveling or like a clean and slim build on your desk. It's only 8.25mm thick, with a huge battery so you won't have to charge it every day. It even has a status LED to tell you when the battery is low. Being wireless, it can connect to any device. Using ZMK firmware, you can customize your layout on the fly inside your browser, and its really power efficient!

---

## Features

- 36 key split layout
- Wireless BLE with ZMK
- Cherry ULP switches
- Reversible PCB design

---

## BOM
 
| Part | Qty | Specification | Price | Link |
|------|-----|---------------|-------|------|
| MCU | 2 | Seeed XIAO nRF52840 | $26.18 | [mauser.pt](https://mauser.pt/095-1482/seeed-102010448-microcontrolador-seeed-studio-xiao-nrf52840-c-bluetooth-5-0-ble-nfc-e-carregamento-de-bateria) |
| Switches (pack of 10) | 4 | Cherry ULP | $41.63 | [keeb.supply](https://keeb.supply/products/cherry-mx-ulp?variant=a840d9fa-f4e0-4218-be04-4d0f5e8f7554) |
| PCBs | 5 | Reversible, MOQ 5 | $11.06 | [jlcpcb.com](https://jlcpcb.com) |
| Batteries | 2 | 307095, 5000mAh battery | $16.23 | [aliexpress.com](https://pt.aliexpress.com/item/1005009973979747.html) |
| Diodes | 36 | SOD-123 | $1.57 | [aliexpress.com](https://pt.aliexpress.com/item/1005012163356976.html) |
| Power Switch | 2 | MK-12C02 | $0.87 | [aliexpress.com](https://pt.aliexpress.com/item/1005011530988236.html) |
| Reset Switch | 2 | EVQ-PUL02K | $1.87 | [aliexpress.com](https://pt.aliexpress.com/item/1005010726427079.html) |
| LEDs | 2 | WS2812B | $1.14 | [aliexpress.com](https://pt.aliexpress.com/item/1005008739048100.html) |
| Case | 2 | | $6.42 | [jlc3dp.com](https://jlc3dp.com) |
| Keycaps | 36 | Resin Printed | $37.46 | [jlc3dp.com](https://jlc3dp.com) |
| Magnets | 8 | 5x2mm round magnets | $2.88 | [aliexpress.com](https://pt.aliexpress.com/item/1005009605352565.html) |
| **Total** | | | **$147.31** | |

---


## Soldering notes

Because the PCB is reversible, some of the pins need to be reversed by bridging solder jumpers. Solder all 5 points shown in the images below for each side.

| Left | Right |
|:---:|:---:|
| ![solder_left](assets/left%20solder.png) | ![solder_right](assets/right%20solder.png) |

---

## Pictures

| |
|:---:|
| **Blueprint**<br><br>![blueprint](assets/blueprint.png) |
| **Schematic**<br><br>![schematic](assets/schematic.png) |
| **PCB**<br><br>![pcb](assets/pcb.png) |
| **Zine**<br><br>[![zine](assets/zine.png)](assets/zine.pdf)<br>[Full PDF](assets/zine.pdf) |


