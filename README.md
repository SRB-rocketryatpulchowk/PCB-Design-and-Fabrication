This repository contains all the KiCad libraries and footprints for components commonly used in our avionics systems.  
Supported KiCad versions: **7.0** and **8.0** (libraries and footprints are cross-compatible between these versions).

---

## Steps to Fabricate PCBs:

### 1. PCB Layout Printing
- Open your PCB design.
- Print (`Ctrl + P`) the **top copper layer (F.Cu)**.
- **Important:**  
  - Check if mirroring is needed. Generally, **we do *not* mirror** the design.
  - Save the print as a **PDF**.

### 2. Arrange Multiple Copies
- Open the saved PDF in **Inkscape**.
- Arrange **as many PCB layouts** as possible into a single **A4 page** to maximize space.
- Save the modified PDF and send it to **Om Dai** for printing.
- Bring the **hard copy** back.

### 3. Toner Transfer (Transferring Design onto Copper Plate)
There are two methods:

- **Hot Method (Iron Method — Recommended)**
  - Place the printed sheet over the copper plate.
  - Use a hot iron to press and heat for about **5–10 minutes**.
  - Let it cool until touchable.
  - Peel off the paper gently.

- **Cold Method (Optional)**
  - Apply **acetone** (nail polish remover) over the paper and copper.
  - Apply static pressure for an extended period.
  - (Not as reliable as the hot method.)

### 4. Etching (Removing Unwanted Copper)
- Prepare an etching solution:  
  **Mix Concentrated Hydrochloric Acid (HCl) and Hydrogen Peroxide (H₂O₂) in a 1:3 ratio.**
- Soak the copper plate in the solution.
- The exposed copper areas will dissolve, leaving only your PCB tracks.

> *(The copper is converted into cupric chloride/oxide during this process.)*

### 5. Cleaning and Drilling
- Clean the etched PCB thoroughly. And check continuity
- Drill component holes using a **1 mm** or **0.8 mm** drill bit.
- Use the milling setup at the Robotics Club if available.

### 6. Soldering and Assembly
- After drilling, proceed to **solder** your components onto the PCB.

---

## Final Tip:
- **Good luck!**
  Make sure to double-check your connections before powering up the board. 🚀

---
