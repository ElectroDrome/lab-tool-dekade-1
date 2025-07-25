
# 🧪 Lab Tool – Precision Resistance Decade (Version 1.0/25)

![PCB Preview](img/decade1_final.jpg)/

---

## 📦 Project Overview

This modular precision resistance decade provides 17 adjustable resistance stages from **10 Ω to 2 MΩ**, using high-quality **25-turn Bourns trimmers** mounted on a custom PCB. Ideal for analog testing, calibration workflows, and educational labs, this decade design emphasizes modularity, clarity, and reliability — perfect for engineers, experimenters, and machine logic hobbyists.

---

## 📦 Project Files

- 📄 [Bill of Materials (BOM)](./bom/bom.csv) – Complete list of components and values  
- 🖼️ [Circuit Schematic (PNG)](./img/decade1_schematics.png) – Visual overview of the circuit
- 🧪 [Gerber Files](./gerber/decade1_gerber.zip) – PCB production files  

---

## 🌟 Features

- 🔁 **17 resistance stages** from 10 Ω to 2 MΩ  
- 🎚️ **Bourns precision potentiometers** (25-turn, 0.5 W, max 900 V)  
- 📌 **Summed output** and **single-value taps** for each stage  
- ⚡ Up to **100 mA load capacity** per trimmer (varies by stage)  
- 🧰 Direct pinheader access to each tap & screw terminal for summed output  
- 📐 KiCad layout with clean ground routing and logical spacing  
- 🪛 Mountable grid PCB for breadboard alignment & enclosure integration  
- 🖨️ Clearly labeled silkscreen with nominal values and tap references  
- 🔓 Licensed Open Hardware (CERN-OHL and CC-BY-SA)

---

## 🧰 Applications

- Sensor calibration and analog simulation  
- RC circuit prototyping and pulse shaping  
- OpAmp testing with predictable resistance  
- PWM-based analog filter loading  
- Reference resistor in microcontroller or LabVIEW experiments  
- Machine logic debugging and voltage divider tuning  

---

## 🔧 Build Specifications

| Attribute              | Value                                 |
|------------------------|----------------------------------------|
| Resistance Range       | 14 Ω – ~3.93 MΩ measured (nominal 10 Ω–2 MΩ)  
| Adjustments            | 25-turn linear Bourns trimmers  
| Tolerances             | ±10% trimmer tolerance (nominal), plus measured deviation  
| Max Voltage            | 900 V DC across stages  
| Power Dissipation      | 0.5 W max per potentiometer  
| PCB Size               | Grid-compatible (standard mounting)  
| Output Taps            | Individual tap headers + summed terminal  

---

## 📊 Measured Values (Stage-to-Stage Overview)

| Tap      | Nominal Value | Measured Min | Measured Max |
|----------|----------------|--------------|--------------|
| R10      | 10 Ω           | 0.1 Ω        | 13.8 Ω       |
| R20      | 20 Ω           | 0.1 Ω        | 22.4 Ω       |
| R50      | 50 Ω           | 0.1 Ω        | 53.3 Ω       |
| R100     | 100 Ω          | 0.1 Ω        | 105 Ω        |
| R200     | 200 Ω          | 0.1 Ω        | 197.1 Ω      |
| R500     | 500 Ω          | 0.1 Ω        | 507.1 Ω      |
| R1K      | 1 kΩ           | 0.3 Ω        | 1.014 kΩ     |
| R2K      | 2 kΩ           | 1.3 Ω        | 1.953 kΩ     |
| R5K      | 5 kΩ           | 0.1 Ω        | 4.656 kΩ     |
| R10K     | 10 kΩ          | 0.1 Ω        | 9.830 kΩ     |
| R20K     | 20 kΩ          | 0.1 Ω        | 19.840 kΩ    |
| R50K     | 50 kΩ          | 0.1 Ω        | 49.400 kΩ    |
| R100K    | 100 kΩ         | 0.3 Ω        | 108.000 kΩ   |
| R200K    | 200 kΩ         | 0.2 Ω        | 201.500 kΩ   |
| R500K    | 500 kΩ         | 0.1 Ω        | 491.600 kΩ   |
| R1M      | 1 MΩ           | 0.3 Ω        | 960 kΩ       |
| R2M      | 2 MΩ           | 0.3 Ω        | 2.083 MΩ     |

🔁 **Total summed output measured: ~3.8 Ω – 3.93 MΩ**

🧠 *Note*: Slight deviations due to trimmer tolerance, contact resistance, temperature drift. No calibration applied — raw measurement data.

---

## 🛠️ Usage Tips

- 🔍 For highest precision: use **low current during measurement**, and **4-wire Kelvin sensing** where possible  
- 📎 Tighten taps with clean leads or clipped headers for minimal contact noise  
- 🔧 Use active load or microcontroller ADC for dynamic feedback calibration  
- 🧪 When combining multiple stages, consider total series resistance and parasitics  
- 🌡️ Keep temperature stable to avoid thermal drift in high-ohm ranges

---

## 📐 PCB Layout Highlights

- Grid-aligned mounting holes  
- Ground plane continuity with star output topology  
- Silkscreen identifiers for each trimmer + tap point  
- Clear trace widths and pad spacings for easy soldering and rework

![Layout Preview](img/dekade1_schema.svg)

---

## 🧪 PCB

![decade-1](img/decade1_pcb.jpg)

---

## 🧪 PCB Prototype

![decade-1](img/decade1_prototype.jpg)

---

## 🔓 License

This project is licensed as Open Hardware under the
- **Hardware** (schematics, layouts, power) [CERN-OHL-P v2](./CERN_OHL_S_v2.txt) for (schematics, layouts, power)
- **Documentation** (Markdown, diagrams) [Creative Commons Attribution ShareAlike](./CC_BY-SA_4.0.txt) 

All product names, logos, and brands are property of their respective owners and used in this website are for identification and educational purposes only. Use of these names, logos, and brands does not imply endorsement.

---
