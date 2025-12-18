# The Void Macro Pad (RP2040)

![Top View Render](/Screenshot 2025-12-18 151251.png)
*> A programmable, open-source mechanical keypad powered by the Seeed XIAO RP2040.*

## 📖 Overview
The **Void Macro Pad** is a custom 3x3 [or 4x4, update this number] mechanical keyboard designed to speed up workflows in Blender, KiCad, and coding. It runs on **CircuitPython (KMK Firmware)**, making it incredibly easy to remap keys just by editing a text file on the USB drive.

It features hot-swap switch sockets, a rotary encoder for volume/zoom control, and a compact footprint perfect for travel.

### ✨ Key Features
* **MCU:** Seeed Studio XIAO RP2040 (Dual-core ARM Cortex M0+).
* **Switches:** Compatible with Cherry MX / Kailh Choc mechanical switches.
* **Firmware:** Powered by [KMK Firmware](https://github.com/KMKfw/kmk_firmware) (Python-based).
* **Connectivity:** USB-C (HID Keyboard + Serial).
* **Customizable:** RGB underglow support and unlimited layers.

---

## 🛠️ Hardware & Bill of Materials (BOM)

| Component | Quantity | Description | Reference |
| :--- | :--- | :--- | :--- |
| **Microcontroller** | 1 | Seeed XIAO RP2040 | U1 |
| **Switches** | 9 | Cherry MX or Kailh Mechanical Switches | SW1 - SW9 |
| **Keycaps** | 9 | DSA or XDA Profile Keycaps | - |
| **Diodes** | 9 | 1N4148 Signal Diodes (Through-hole or SOD-123) | D1 - D9 |
| **Sockets** | 9 | Kailh Hot-Swap Sockets (Optional) | - |
| **Rotary Encoder** | 1 | EC11 Encoder with Push Button (Optional) | ENC1 |

*Full parts list available in [BOM.csv](./BOM.csv).*

---

## 🔌 Pinout & Wiring

This board uses a standard matrix (or direct pin) layout.

| Function | XIAO Pin | Description |
| :--- | :--- | :--- |
| **Row 1** | D0 | Switch Row 1 |
| **Row 2** | D1 | Switch Row 2 |
| **Row 3** | D2 | Switch Row 3 |
| **Col 1** | D8 | Switch Column 1 |
| **Col 2** | D9 | Switch Column 2 |
| **Col 3** | D10 | Switch Column 3 |
| **Encoder A** | D3 | Rotation A |
| **Encoder B** | D4 | Rotation B |

---
