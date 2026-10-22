# Supplementary Data: Rectangular Shaft Experiments (Appendix 1)

This repository contains the supplementary experimental time series, phase segmentation analyses, and aerodynamic measurements for the rectangular shaft testing campaign reported in the **FunctionalSkin** project (*Major Innovation Project, MSc Bio Inspired Innovation, Utrecht University*).

---

## 1. Experimental Overview

The rectangular shaft experiments evaluated the convective cooling and thermal buffering capacity of naturally ventilated façade panel configurations under controlled laboratory conditions.

* **Panel Dimensions:** All test assemblies measured $600\text{ mm (height)} \times 300\text{ mm (width)}$ and were mounted vertically onto a uniform $12\text{ mm}$ plywood backboard.
* **Cavity Geometry:** Nominal cavity depth was $80\text{ mm}$ (with the exception of the Deep Cavity configuration, which measured $160\text{ mm}$).
* **Simulated Solar Irradiance:** Panels were continuously exposed to simulated solar radiation using dual $1000\text{ W}$ halogen lamps (Fenon R7s) calibrated to deliver an average flux of $790.7 \pm 17.6\text{ W}\cdot\text{m}^{-2}$ (monitored via an SL 200 solarimeter).
* **Experimental Protocol:**
  * **Baseline Phase ($0 - 10\text{ min}$):** Initial ambient thermal equilibrium prior to lamp activation.
  * **Heating Phase ($10 - 130\text{ min}$):** Active lamp exposure inducing transient temperature rise and transition into quasi-steady-state plateau conditions.
  * **Cooling Phase ($130 - 190\text{ min}$):** Lamps switched off; post-exposure natural convective cooling.
* **Automated Phase Segmentation:** The onset of the quasi-steady-state plateau phase was determined independently for each sensor using the **Kneedle knee-detection algorithm** (Satopaa et al., 2011) applied to the heating segment.

---

## 2. Sensor Layout and Instrumentation

Each multi-panel figure (Figures A1–A9) presents synchronized, $10\text{-second}$ resampled time-series data grouped into six standardized sub-panels:

| Sub-Panel | Sensor Identifier | Sensor Type | Measurement Location |
| :--- | :--- | :--- | :--- |
| **(a)** | **STBB** | Type K Thermocouple | Rear surface of the interior plywood backwall ($12\text{ mm}$) |
| **(b)** | **STBI** | Type K Thermocouple | Cavity-facing inner surface of the plywood backwall |
| **(c)** | **STFI** | Type K Thermocouple | Cavity-facing surface of the exterior façade cladding |
| **(d)** | $T_{\text{top}}$ | Testo 605i Thermo-hygrometer | Cavity air temperature near the upper exhaust opening |
| **(e)** | $T_{\text{bottom}}$ | Testo 605i Thermo-hygrometer | Cavity air temperature near the lower air intake opening |
| **(f)** | $v_{\text{air}}$ | Testo 410i / 405i Anemometer | Airflow velocity measured at the upper cavity exhaust |

*Phase delineation:*
* **Phase 1 (Red dotted line):** Active heating phase ($10\text{ min}$ mark).
* **Phase 2 (Green dotted line):** Sensor-specific quasi-steady-state plateau onset ($t_{\text{plateau}}$).
* **Phase 3 (Blue dotted line):** Post-exposure cooling phase ($130\text{ min}$ mark).

*In-plot annotations:* Report mean plateau values ($T_{\text{plateau}}$, $v_{\text{plateau}}$), standard deviations ($\text{SD}$), and hourly rates of change ($\Delta T$, $\Delta v$).

---
## 3 Supplementary Figures: Shaft Experiments

### Figure A1
**Sensor response and automated phase segmentation for the Negative Control configuration (sealed lower aperture).**  
Multi-panel time series display transient and plateau values of surface thermocouples attached to:
* **(a)** Backside of the plywood backwall (STBB)
* **(b)** Cavity-facing surface of the backwall (STBI)
* **(c)** Cavity-facing surface of the cladding (STFI)
* **(d)** Upper cavity air temperature probe
* **(e)** Lower cavity air temperature probe
* **(f)** Airflow velocity sensor

The three experimental phases are delineated by vertical dotted lines: 
1. **Heating phase** (red, 1)
2. **Quasi-steady-state plateau phase** (green, 2)
3. **Natural cooling phase** (blue, 3)

In-plot annotations report mean plateau values (*T*<sub>plateau</sub>, *v*<sub>plateau</sub>), standard deviations (*SD*), and hourly rates of change (Δ*T*, Δ*v*).  
*Key finding:* Sealing the lower aperture prevented buoyancy airflow (*v* = 0.45 m/s, dominated by internal recirculation), resulting in thermal trapping and high backwall heating (STBI = 44.3 °C).

---

### Figure A2
**Sensor response and automated phase segmentation for the Standard Panel.**  
*(a)–(f) as labelled in Figure A1.*  
*Key finding:* Opening the cavity established continuous buoyancy-driven airflow (*v* = 0.71 m/s), setting up a vertical cavity gradient (Δ*T*<sub>cavity</sub> = 7.2 °C) and lowering inner backwall temperature to STBI = 39.8 °C.

---

### Figure A3
**Sensor response and automated phase segmentation for the Deep Cavity configuration.**  
*(a)–(f) as labelled in Figure A1.*  
*Key finding:* An extended warming time (*t*<sub>plateau</sub> = 1.77 h) reflects the increased thermal buffering and mass throughput of the 160 mm cavity cross-section. It achieved the highest airflow velocity (*v* = 0.79 m/s), maximum sensible heat removal (Q̇<sub>air</sub> = 254.8 W), and lowest backwall temperature (STBI = 33.9 °C).

---

### Figure A4
**Sensor response and automated phase segmentation for the 9 mm Plywood Panel configuration.**  
*(a)–(f) as labelled in Figure A1.*  
*Key finding:* Profiles highlight the thermal delay (*t*<sub>plateau</sub> = 1.43 h) and a pronounced vertical temperature gradient (Δ*T*<sub>cavity</sub> = 9.3 °C) caused by increased cladding thickness, removing 143.4 W of sensible heat while maintaining STBI at 37.9 °C.

---

### Figure A5
**Sensor response and automated phase segmentation for the 12 mm Plywood Panel configuration.**  
*(a)–(f) as labelled in Figure A1.*  
*Key finding:* Further increase in cladding mass lowered backwall heating (STBI = 35.0 °C) with an air velocity of 0.70 m/s and a thermal delay of *t*<sub>plateau</sub> = 1.35 h, confirming that thicker cladding improves conductive resistance without restricting ventilation.

---

### Figure A6
**Sensor response and automated phase segmentation for the High-Albedo Coated Panel (Trial 1).**  
*(a)–(f) as labelled in Figure A1.*  
*Key finding:* Application of high-albedo reflective coating (Arcareflect 1198) mitigated radiant absorption, lowering the inner backwall temperature to STBI = 37.5 °C with a plateau heat transport rate of Q̇<sub>air</sub> = 109.5 W.

---

### Figure A7
**Sensor response and automated phase segmentation for the High-Albedo Coated Panel (Trial 2).**  
*(a)–(f) as labelled in Figure A1.*  
*Key finding:* Independent replicate run evaluating measurement repeatability across surface temperatures, cavity air gradients (Δ*T*<sub>cavity</sub> = 7.3 °C), and convective air velocity (*v* = 0.69 m/s).

---

### Figure A8
**Sensor response and automated phase segmentation for the CryoPaint Coated Panel (Trial 1).**  
*(a)–(f) as labelled in Figure A1.*  
*Key finding:* Tested with three layers of radiative cooling CryoPaint®. Passive radiative emission combined with natural convection held the backwall temperature down to STBI = 36.3 °C, with an airflow velocity of *v* = 0.72 m/s and Q̇<sub>air</sub> = 126.4 W.

---

### Figure A9
**Sensor response and automated phase segmentation for the CryoPaint Coated Panel (Trial 2 / Replicate).**  
*(a)–(f) as labelled in Figure A1.*  
*Key finding:* Validation run confirming experimental repeatability under constant simulated solar irradiation (~787 W/m²), demonstrating consistent phase transitions (*t*<sub>plateau</sub> ≈ 0.97 h) and stable convective cooling dynamics.

---

## Performance Summary Table

| Configuration | Δ*T*<sub>cavity</sub> (°C) | *v*<sub>air</sub> (m/s) | Q̇<sub>air</sub> (W) | STBI (°C) | *t*<sub>plateau</sub> (h) | Irradiance (W/m²) |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Negative Control** | 0.6 | 0.452 | 5.9 | 44.3 | 1.20 | 800 |
| **Standard Panel (5.5 mm)** | 7.2 | 0.707 | 111.0 | 39.8 | 0.96 | 778 |
| **Deep Cavity (160 mm)** | 7.4 | 0.789 | 254.8 | 33.9 | 1.77 | 774 |
| **9 mm Plywood** | 9.3 | 0.714 | 143.4 | 37.9 | 1.43 | 820 |
| **12 mm Plywood** | 8.1 | 0.701 | 123.0 | 35.0 | 1.35 | 804 |
| **High-Albedo Coated** | 7.3 | 0.691 | 109.5 | 37.5 | 1.04 | 772 |
| **CryoPaint® Coated** | 8.1 | 0.721 | 126.4 | 36.3 | 0.97 | 787 |
