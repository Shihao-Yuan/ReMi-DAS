# **ReMi-DAS**  
**Refraction Microtremor Processing for Distributed Acoustic Sensing Data**

**DAS-ReMi** is an open-source toolkit for applying Refraction Microtremor (ReMi) analysis to Distributed Acoustic Sensing (DAS) data.  
It extends conventional ReMi workflows to accommodate strain/strain-rate measurements from DAS arrays, enabling efficient and scalable shear-wave velocity (Vs) profiling—particularly in urban or infrastructure-constrained environments.

This package is developed using core functionality from the [**DASCore**](https://github.com/DASDAE/dascore/tree/master) project — a flexible Python library for reading, processing, and visualizing DAS data.

---

### 🔧 Features

- 📓 A Jupyter notebook demonstrating the complete ReMi workflow
- 🧩 Modular Python scripts for:
  - Preprocessing DAS data (e.g., tapering, filtering)
  - Slowness-frequency transformation using Tau-P methods
  - Dispersion curve picking and visualization
- 📊 Tools for slowness-frequency image plotting and Rayleigh-wave dispersion analysis

---

### 📂 Project Structure

```bash
DAS_ReMi/
├── notebooks/        # Jupyter demonstration notebooks
├── LICENSE           # MIT License
├── README.md         # Project description and usage
├── requirements.txt  # Python dependencies
└── setup.py          # Packaging config

