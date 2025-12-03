# Aillio Bean Stirrer  
### Open Hardware Release • Designed by Dustin Betterly

<img src="images/hero_render.png" width="900"/>

The **Aillio Bean Stirrer** is an open-hardware accessory designed for the **Aillio R1 and R2 cooling bowls**.  
Its purpose is simple: **speed up the cooling cycle and help remove any chaff that didn’t escape during roasting.**

By actively agitating the beans during cooling, the stirrer:
- Accelerates heat dissipation  
- Improves airflow through the bean mass  
- Breaks up clumps for more uniform cooling  
- Helps eject additional trapped chaff  
- Reduces total cooling time compared to passive airflow alone  

**This tool is for post-roast cooling only.  
It is NOT designed for use inside the roasting drum.**

---

## ✨ Features
- Rapid bean agitation for faster, more uniform cooling  
- Helps remove residual chaff that didn’t exit the drum  
- High-temperature stir paddle (PA6-CF recommended)  
- Wear-friendly PTFE washer system  
- Completely printable housing, paddle, and thumb screws  
- Tested for safe use with hot roasted beans  
- Open hardware — remix, improve, share

---

## 📦 Repository Contents


---

## 🧰 Bill of Materials (BOM)

See:  
- `BOM/Bill_of_Materials.csv`  
- `docs/Exploded_View.pdf`  

Key hardware:
- **80 mm stainless square rod** (cut to length)  
- PTFE shoulder washers  
- Heat-set inserts  
- Assorted M3/M5 fasteners  
- 12 V DC motor (reverse-rotation supported)

---

## 🛠 Material Recommendations

| Part | Material | Brand | Notes |
|------|----------|--------|-------|
| Stir Paddle | **PA6-CF** | Polymaker Fiberon | High heat deflection so **hot beans won’t deform** it |
| Wear Plates | PA6-CF | Polymaker Fiberon | Low friction + heat resistant |
| Housing / Covers | PLA-CF | Bambu Labs | Rigid, stable, clean finish |
| Thumb Screws | PLA-CF | Bambu Labs | Strong and easy to bond to steel screws |

---

## 🪚 Cutting the Square Rod (80 mm)

The square stainless bar must be cut to **80 mm** final length.

**Steps:**
1. Mark 80 mm with calipers  
2. Cut using hacksaw, metal bandsaw, or cutoff wheel  
3. Deburr ends with file or sandpaper  
4. Verify smooth sliding fit in the hubs  
5. Acceptable tolerance: **±0.25 mm**

---

## 🖨 Printing Guidance

### Stir Paddle (PA6-CF)
- Print **upside-down**  
- Supports: *build plate only*  
- Add pause to insert embedded nut  
- Optional: Resin coat + sand for smooth finish

### Thumb Screws
- Pause print to insert M5 screw  
- Secure using resin or cyanoacrylate

### General Guidance
- Layer height: 0.2–0.24 mm  
- Infill: 30–40% gyroid or cubic  
- Walls: 4–6  
- Hardened nozzle recommended for CF filaments

---

## 🔧 Assembly Overview

Refer to:  
`docs/Exploded_View.pdf`

General notes:
- Center the stir paddle on the bowl’s middle pin  
- Do **not** overtighten the paddle screw  
- Leave motor screws slightly loose for initial alignment  
- Apply blue Loctite after final positioning

---

## ⚡ Motor & Power

- Uses a 12 V DC motor  
- If the paddle spins backward → **swap + and – wires**  
- 12 V 2 A power supply recommended  

---

## 🛡 License — CC BY-NC 4.0

You may:
- Print and remix for personal use  
- Share non-commercially  
- Must credit: **Dustin Betterly**

You may NOT:
- Sell the files  
- Sell printed parts or kits  
- Use commercially without permission  

Full text: https://creativecommons.org/licenses/by-nc/4.0/

---

## 🙌 Credits

**Design & documentation:**  
Dustin Betterly

**Render:**  
Included in `images/hero_render.png`

---

## 🗂 Version History

### **v1.0 — Initial Public Release**
- Updated exploded view  
- Complete manual  
- Finalized CAD, STEP, and STL files  
- Corrected purpose (cooling + chaff removal)  
- CC BY-NC license applied  

---

> **If you build it, share your results!  
Pull requests, improvements, and remixes are welcome.**

