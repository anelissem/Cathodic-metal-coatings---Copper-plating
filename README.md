# 🧪 Copper Plating Simulation – Cathodic Metal Deposition

## 👩‍🔬 Authors  
**Popescu Anelisse Maria**  
**Zgavarogea Mihai**

---

## 📘 Project Overview

This project is an **interactive web application** designed to simulate the **cathodic deposition of metals**, focusing on the **copper plating (cuprarea)** process via **electrolysis**.  

The goal is to create an **educational and visual tool** that demonstrates the physical and chemical principles of metal deposition, helping students and teachers better understand the relationship between electric current, time, and deposited mass according to **Faraday’s laws of electrolysis**.

---

## ⚙️ Features

- 🌐 **Fully interactive web interface** – accessible directly from a browser  
- ⚡ Adjustable parameters:  
  - Electric current intensity (A)  
  - Process duration (minutes)  
  - Cathode surface area (cm²)  
- 📊 **Automatic calculations** for:  
  - Theoretical mass deposited  
  - Actual deposited mass (based on efficiency)  
  - Current efficiency  
  - Layer thickness (µm)  
- 🎞️ **Animated visualization** of the electrolysis process:
  - Movement of copper ions (Cu²⁺) and electrons  
  - Copper layer forming dynamically on the cathode  
  - Air bubbles and plating effects for realism  
- 🔄 **Reset and replay functionality** for multiple simulation runs  
- 📚 **Documentation links** to the theoretical background and full experiment details

---

## 🧠 Scientific Background

The **copper plating process** involves depositing a thin layer of copper on a metallic surface (usually iron or brass) through the passage of electric current in a **copper sulfate (CuSO₄)** solution.

**Electrochemical reactions involved:**

- **At the cathode (metal surface to be plated):**  
  \[
  Cu^{2+} + 2e^- \rightarrow Cu (s)
  \]

- **At the anode (copper plate):**  
  \[
  Cu (s) \rightarrow Cu^{2+} + 2e^-
  \]

The **mass of copper deposited** is directly proportional to the electric charge passed through the electrolyte, as described by **Faraday’s Law of Electrolysis**:

\[
m = \frac{M \cdot I \cdot t}{n \cdot F}
\]

Where:  
- *m* – mass of the deposited metal (g)  
- *M* – molar mass of copper (63.546 g/mol)  
- *I* – current intensity (A)  
- *t* – time (s)  
- *n* – number of electrons exchanged (2 for Cu²⁺)  
- *F* – Faraday constant (96500 C/mol)

---

## 💻 Technologies Used

- **HTML5**, **CSS3**, **JavaScript** – for user interface, logic, and animations  
- **Embedded Physics & Chemistry formulas** – for real-time computation  
- **Responsive design** – adaptable to different screen sizes  
- **Dynamic animation engine** – implemented via JavaScript’s `requestAnimationFrame()`  

---

## 🧩 File Description

### `rezultate.html`
Main simulation file.  
Includes:
- Interactive control panel for input parameters  
- Real-time results section displaying mass, efficiency, and thickness  
- Animated representation of copper ions, electrodes, and electrons  
- Links to experiment documentation (`7. Depuneri catodice de metale. Cuprarea.pdf`) and an additional simulation page (`copie.html`)

---

## 🚀 How to Run the Application

1. **Download or clone** the repository containing `rezultate.html`.  
2. Ensure all required files are in the same directory:
   - `rezultate.html`
   - `background.jpg` (optional, for background image)
   - `copie.html`
   - `7. Depuneri catodice de metale. Cuprarea.pdf`
3. Open `rezultate.html` in any modern web browser (Chrome, Edge, Firefox).  
4. Adjust the simulation parameters and click **“Start Electrolysis”** to begin the experiment.

---

## 📊 Example Outputs

| Parameter | Example Value | Description |
|------------|----------------|--------------|
| Current (A) | 0.3 | Adjusted via slider |
| Time (min) | 30 | Total electrolysis time |
| Surface (cm²) | 20 | Cathode area |
| Theoretical Mass | ~0.6 g | Calculated via Faraday’s Law |
| Efficiency | 90% | Default simulation efficiency |
| Layer Thickness | ~3 µm | Calculated result |

---

## 🎓 Educational Use

This application is intended for **chemistry laboratories, high schools, and universities**, providing:
- A safe and interactive way to study electrolysis without chemicals  
- A clear **visual understanding of ion movement** and metal deposition  
- Direct application of **Faraday’s law and density-based calculations**

---

## 📁 Project Structure

