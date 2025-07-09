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

### References

- McMechan, G.A. and Yedlin, M.J., 1981. Analysis of dispersive waves by wave field transformation. *Geophysics*, 46(6), pp.869-874.  
- Louie, J.N., 2001. Faster, better: shear-wave velocity to 100 meters depth from refraction microtremor arrays. *BSSA*, 91(2), pp.347-364. 
- Chambers, D., Jin, G., Tourei, A., Issah, A.H.S., Lellouch, A., Martin, E.R., Zhu, D., Girard, A.J., Yuan, S., Cullison, T. and Snyder, T., 2024. Dascore: A python library for distributed fiber optic sensing. *Seismica*, 3(2), pp.10-26443.

