# Fixed-Wing Aircraft Design & Aerodynamic Analysis
**0.75m Span UAV | OpenVSP & VSPAERO Analysis | Fusion 360 Integration**

---

### 1. Aerodynamic Modeling & Analysis
* **Geometry & Wing Planform:** Designed and modelled three 0.75m span iterations in OpenVSP using a NACA 0006 airfoil (AR 6.1, 0.60 taper ratio) to *approximate an elliptical lift distribution and minimise induced drag*.
* **VLM Cruise Sweep:** Ran VSPAERO VLM baseline sweep at 20m/s *to hit target cruise $C_L = 0.475$, implementing a +3° wing incidence to eliminate nose-up fuselage attitude and reduce parasitic cruise drag*.
* **Trim & Stability Analysis:** Executed trim analysis to evaluate lift, drag, pitching moments, and stability across 10 angles of attack. Calculated CoG placement via VLM results *to guarantee a 10–15% static margin*.
* **Flow Verification:** Analysed generated graphs to verify pressure and wake distributions, ensuring no premature tip stalls occurred

---

### 2. Detailed CAD & Physical Prototyping
* **Internal Structural Design:** Modelled full assembly in Autodesk Fusion including *internal electronics bays, servo nests, energy-absorbing elastic wing mounts, and internal wing structure* to ensure simplicity during manufacturing.
* **BOM & Prototyping:** Delivered a complete Bill of Materials (BOM) total: **£90**. Built original proof-of-concept prototype using a pre-made fixed-wing glider frame; current iteration is actively undergoing full-scale 3D printing.

---

### 3. Project Figures & Documentation

| Figure 1 | Figure 2 |
| :---: | :---: |
| **Figure 1:** OpenVSP Geometry & Wing Planform Layout | **Figure 2:** VSPAERO Vortex Lattice Method (VLM) Mesh |
| ![Figure 1](openvsp) | ![Figure 2](wake) |

| Figure 3 | Figure 4 |
| :---: | :---: |
| **Figure 3:** Lift Distribution curve | **Figure 4:** Pressure Gradients |
| ![Figure 3](cl) | ![Figure 4](pressure) |

| Figure 5 | Figure 6 |
| :---: | :---: |
| **Figure 5:** Original Fusion 360 iteration with internal Bay & Servo Layout | **Figure 6:** Second Fusion 360 iteration with Elastic Wing Mount  |
| ![Figure 5](cad1) | ![Figure 6](cad2) |




