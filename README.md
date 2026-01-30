# FEAX — Minimal 2D Truss & Frame Finite Element Analysis Simulation


**FEAX** is a lightweight, browser-based **Finite Element Analysis (FEA) tool** for 2D truss and frame/beam structures. Build structures, apply loads and supports, and visualize displacements and stresses—all in real-time directly in your browser.

---

##  Features

- **Element Types:** Truss (axial only), Frame/Beam (axial + bending)  
- **Materials:** Steel, Aluminum, PLA + custom material properties  
- **Supports:** Pin, Roller, Fixed  
- **Loads:** Point forces/moments, UDL, gravity toggle  
- **Visualization:**  
  - Interactive 2D canvas  
  - Stress-based coloring (tension = red, compression = blue)  
  - Deformed shape overlay  
  - Hover for detailed node/bar info  
- **Tools:** Node, Bar, Support, Load, Select  
- **File Management:** Save/load JSON models  

---

##  Live Demo

Open the simulation directly in your browser (no server required):

[Open `index.html`](./index.html)

---

##  Quick Start

1. **Clone or download** this repository.  
2. **Open `index.html`** in a modern browser (Chrome, Firefox, Edge).  
3. **Add nodes** using the “Node” tool.  
4. **Connect nodes** with bars using the “Bar” tool.  
5. **Assign materials and cross-sections** to bars.  
6. **Apply supports** (Pin, Roller, Fixed) to nodes.  
7. **Apply loads** (forces, moments, or UDL).  
8. **Click “Solve”** to see displacements and stresses.  
9. **Adjust deformation scale** to inspect the results visually.  

---

## ⚙️ Controls

| Action | Control |
|--------|---------|
| Pan view | Hold `Alt` + drag |
| Zoom | Mouse wheel |
| Select node/bar | Click |
| Drag node | Click & drag |
| Add node | Select “Node” → click canvas |
| Add bar | Select “Bar” → click two nodes |
| Apply support | Select “Support” → click node |
| Apply load | Select “Load” → click node |

---

##  File Structure

FEAX/
├── index.html # Main HTML page
├── style.css # Styles (optional)
├── script.js # Simulation & FEA logic
├── README.md # This file


---

##  How It Works

- Assembles a **global stiffness matrix** for truss/frame elements  
- Handles **support constraints**  
- Computes **nodal displacements** and **element forces**  
- Visualizes **stress and deformation** on the canvas  

---

##  Future Enhancements

- Dynamic simulation (vibrations)  
- 3D FEA support  
- More advanced elements (plates, shells)  
- Plasticity/failure modeling  
- Export results to PNG/SVG  


##  Author

**Arthur Tai** — Educational FEA simulation built with HTML5 & JavaScript
