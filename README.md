# PARSA.HM-SLB-001 – Scissor Lift Assembly

A complete 3D CAD design of a **hydraulic scissor lift mechanism** created in SOLIDWORKS.

This project includes individual part models, the complete assembly, rendered images, and an exploded view animation.

---

## Assembly Render

![Scissor Lift Assembly](RENDERS/Scissors%20Lift%20Assembly%20render/Scissor-Lift-Assembly-Render.jpg)

---

## Project Overview

This project is a fully functional, manufacturable scissor lift assembly designed for structural evaluation and motion simulation. It includes:

- **13 Unique Parts:** From sheet metal base plates and structural arms to precision machined pins and hydraulic components.
- **Manufacturing Compliance:** All parts are designed according to **ISO 2768-mK** (Medium) tolerances.
- **Standards:** Applied ISO and DIN standards for threads and fits.
- **Load Capacity:** Designed for medium-duty lifting applications (hydraulic actuation).

---

## Assembly Components

The assembly consists of the following parts:

| # | Part Name | File Name |
|---|-----------|-----------|
| 1 | Base Plate | `Bottom Tray.SLDPRT` |
| 2 | Upper Scissor Arm | `Bar.SLDPRT` |
| 3 | Lower Scissor Arm | `Bar.SLDPRT` |
| 4 | Top Platform | `Body.SLDPRT` |
| 5 | Hydraulic Cylinder Body | `Support Cylinder.SLDPRT` |
| 6 | Hydraulic Cylinder Shaft | `Cylinder Shaft.SLDPRT` |
| 7 | Cylinder Head | `Cylinder Head.SLDPRT` |
| 8 | Main Pivot Pins | `Hinge Shaft.SLDPRT` |
| 9 | Short Pivot Pin | `Hinge Shaft Short.SLDPRT` |
| 10 | Wheel Assembly | `Wheel.SLDPRT` |
| 11 | Axle | `Axel and Wheel.SLDPRT` |
| 12 | Turnable Joint | `Turntable.SLDPRT` |
| 13 | Stairs/Steps | `Stairs.SLDPRT` |

---

## Selected Materials

| Component | Material | Standard |
|-----------|----------|----------|
| Base Plate | **Structural Steel (ASTM A36)** | ASTM A36 |
| Upper Scissor Arm | **Structural Steel (ASTM A36)** | ASTM A36 |
| Lower Scissor Arm | **Structural Steel (ASTM A36)** | ASTM A36 |
| Top Platform | **Structural Steel (ASTM A36)** | ASTM A36 |
| Hydraulic Cylinder Body | **Stainless Steel (AISI 304)** | AISI 304 |
| Hydraulic Cylinder Shaft | **Hardened Steel (AISI 4140)** | AISI 4140 |
| Cylinder Head | **Stainless Steel (AISI 304)** | AISI 304 |
| Main Pivot Pins | **Alloy Steel (AISI 4140)** | AISI 4140 |
| Short Pivot Pin | **Alloy Steel (AISI 4140)** | AISI 4140 |
| Wheel Assembly | **Polyurethane / Steel** | - |
| Axle | **Carbon Steel (AISI 1045)** | AISI 1045 |
| Turnable Joint | **Alloy Steel (AISI 4140)** | AISI 4140 |
| Stairs/Steps | **Structural Steel (ASTM A36)** | ASTM A36 |

---

## Technical Features

- **Material Selection:** Structural steel (A36) for load-bearing components, stainless steel (AISI 304) for hydraulic parts, and hardened alloy steel (AISI 4140) for pins and shafts.
- **Hydraulic System:** Integrated cylinder mounting with proper alignment for smooth actuation.
- **Fits & Tolerances:** Applied ISO fits (h9, H11) for mating parts to ensure correct assembly and function.
- **Structural Integrity:** Cross-linked scissor arms designed for optimal load distribution.
- **Mobility:** Wheel assemblies with polyurethane tires for easy positioning.

---

## Exploded View Animation

![Exploded View GIF](EXPLODED%20VIEW/Assem%20Exploded%20View.gif)

[▶ Watch Exploded View Animation (MP4)](EXPLODED%20VIEW/Assem%20Exploded%20View.mp4)

---

## Motor Render Animation

![Motor Render GIF](RENDERS/Assem1%20MOTOR%20RENDER.gif)

[▶ Watch Motor Render Animation (MP4)](RENDERS/Assem1%20MOTOR%20RENDER.mp4)

---

## Project Files

- [SOLIDWORKS Assembly](CAD/ASSEMBLY/Assem1.SLDASM)
- [SOLIDWORKS Part Files](CAD/PARTS/)
- [Rendered Images & Animations](RENDERS/)
- [Exploded View Animation](EXPLODED%20VIEW/)
- [STEP File](STEP%20FILE/Assem%20STEP.STEP)

---

## File Formats

| File Type | Format |
|-----------|--------|
| SOLIDWORKS Parts | `.SLDPRT` |
| SOLIDWORKS Assembly | `.SLDASM` |
| STEP Assembly | `.STEP` |
| Rendered Images | `.JPG` |
| Animations (Exploded View) | `.GIF` / `.MP4` |
| Animations (Motor Render) | `.GIF` / `.MP4` |

---

## Folder Structure

```
Scissor-Lift-SolidWorks/
├── CAD/
│   ├── ASSEMBLY/
│   │   └── Assem1.SLDASM
│   └── PARTS/
│       ├── Axel and Wheel.SLDPRT
│       ├── Bar.SLDPRT
│       ├── Body.SLDPRT
│       ├── Bottom Tray.SLDPRT
│       ├── Cylinder Head.SLDPRT
│       ├── Cylinder Shaft.SLDPRT
│       ├── Hinge Shaft.SLDPRT
│       ├── Hinge Shaft Short.SLDPRT
│       ├── Stairs.SLDPRT
│       ├── Support Cylinder.SLDPRT
│       ├── Turntable.SLDPRT
│       └── Wheel.SLDPRT
├── EXPLODED VIEW/
│   ├── Assem Exploded View.gif
│   └── Assem Exploded View.mp4
├── RENDERS/
│   ├── Scissors Lift Assembly render/Scissor-Lift-Assembly-Render.jpg
│   ├── Assem1 MOTOR RENDER.gif
│   └── Assem1 MOTOR RENDER.mp4
├── STEP FILE/
│   └── Assem STEP.STEP
└── README.md
```
