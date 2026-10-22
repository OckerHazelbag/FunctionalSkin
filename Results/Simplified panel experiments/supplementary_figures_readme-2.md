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

## 3. Supplementary Figure Descriptions

### Figure A1. Sensor response and automated phase segmentation for the Negative Control configuration (sealed lower aperture)

* **Caption:**
  > **Figure A1.** Sensor response and automated phase segmentation for the Negative Control configuration (sealed lower aperture). Multi-panel time series display transient and plateau values of surface thermocouples attached to (a) the backside of the plywood backwall (STBB), (b) the cavity facing surface of the backwall (STBI), (c) the cavity facing surface of the cladding (STFI), supplemented with air temperature probes displaying (d) upper cavity air temperature, (e) lower cavity air temperature, and lastly (f) airflow velocity sensor. The three phases are delineated by vertical dotted lines: heating phase (red, 1), quasi-steady-state plateau phase (green, 2), and natural cooling phase (blue, 3). In-plot annotations report mean plateau values ($T_{\text{plateau}}$, $v_{\text{plateau}}$), standard deviations ($\text{SD}$), and hourly rate of temperature change ($\Delta T$, $\Delta v$).

* **Detailed Description:**
  * **Configuration:** Standard $5.5\text{ mm}$ plywood cladding with an $80\text{ mm}$ cavity, but with the bottom intake opening completely sealed to prevent natural air entry.
  * **Observed Aerodynamics:** The sealed aperture prevents convective flow throughput ($v_{\text{air}} = 0.452\text{ m}\cdot\text{s}^{-1}$, consisting primarily of internal turbulent recirculation rather than net upward draft).
  * **Thermal Response:** The vertical cavity air temperature gradient collapses to $\Delta T_{\text{cavity}} = 0.60^{\circ}\text{C}$, yielding a negligible sensible heat transport rate ($\dot{Q}_{\text{air}} = 5.9\text{ W}$). Heat accumulation produces the highest backwall temperature across all shaft trials ($\text{STBI} = 44.3^{\circ}\text{C}$).

---

### Figure A2. Sensor response and automated phase segmentation for the Standard Panel

* **Caption:**
  > **Figure A2.** Sensor response and automated phase segmentation for the Standard Panel. (a)–(f) as labelled in Figure A1.

* **Detailed Description:**
  * **Configuration:** Open ventilated reference panel ($5.5\text{ mm}$ plywood, $80\text{ mm}$ cavity depth, unsealed intake and exhaust).
  * **Observed Aerodynamics:** Unrestricted intake allows buoyancy-driven natural ventilation to develop rapidly, stabilizing at an exhaust airspeed of $v_{\text{air}} = 0.707\text{ m}\cdot\text{s}^{-1}$.
  * **Thermal Response:** Establishes a vertical cavity gradient of $\Delta T_{\text{cavity}} = 7.2^{\circ}\text{C}$ and removes $\dot{Q}_{\text{air}} = 111.0\text{ W}$ of sensible heat. This chimney effect lowers the backwall surface temperature to $\text{STBI} = 39.8^{\circ}\text{C}$ (an immediate $4.5^{\circ}\text{C}$ cooling benefit relative to the negative control). Thermal equilibrium is reached quickly at $t_{\text{plateau}} = 0.96\text{ h}$.

---

### Figure A3. Sensor response and automated phase segmentation for the Deep Cavity configuration

* **Caption:**
  > **Figure A3.** Sensor response and automated phase segmentation for the Deep Cavity configuration. (a)–(f) as labelled in Figure A1. Extended warming time ($t_{\text{plateau}} = 1.77\text{ h}$) reflects the increased thermal buffering and mass throughput of the enlarged channel cross-section.

* **Detailed Description:**
  * **Configuration:** Cavity depth doubled from $80\text{ mm}$ to $160\text{ mm}$ ($5.5\text{ mm}$ plywood cladding).
  * **Observed Aerodynamics:** The expanded cross-sectional area lowers aerodynamic flow resistance, generating the highest velocity recorded in the shaft series ($v_{\text{air}} = 0.789\text{ m}\cdot\text{s}^{-1}$, an $11.6\%$ increase over the standard panel).
  * **Thermal Response:** While sustaining a cavity gradient of $\Delta T_{\text{cavity}} = 7.4^{\circ}\text{C}$, the enlarged mass flow rate ($\dot{m}_{\text{air}}$) evacuates $\dot{Q}_{\text{air}} = 254.8\text{ W}$ ($+129.5\%$ higher than standard). This delivers the lowest backwall temperature of all shaft assemblies ($\text{STBI} = 33.9^{\circ}\text{C}$), with thermal inertia delaying stabilization to $t_{\text{plateau}} = 1.77\text{ h}$.

---

### Figure A4. Sensor response and automated phase segmentation for the 9 mm Plywood Panel configuration

* **Caption:**
  > **Figure A4.** Sensor response and automated phase segmentation for the 9 mm Plywood Panel configuration. (a)–(f) as labelled in Figure A1. Profiles highlight the thermal delay ($t_{\text{plateau}} = 1.43\text{ h}$) and vertical temperature gradients developed by increased cladding thickness.

* **Detailed Description:**
  * **Configuration:** Cladding thickness increased to $9\text{ mm}$ plywood ($80\text{ mm}$ cavity depth).
  * **Observed Aerodynamics:** Airflow velocity remains stable at $v_{\text{air}} = 0.714\text{ m}\cdot\text{s}^{-1}$, demonstrating that cladding thickness does not restrict cavity convection.
  * **Thermal Response:** The heavier cladding provides thermal mass and conductive resistance, delaying plateau stabilization ($t_{\text{plateau}} = 1.43\text{ h}$). It develops the largest vertical temperature gradient ($\Delta T_{\text{cavity}} = 9.3^{\circ}\text{C}$) and sensible heat removal of $\dot{Q}_{\text{air}} = 143.4\text{ W}$, limiting backwall heating to $\text{STBI} = 37.9^{\circ}\text{C}$.

---

### Figure A5. Sensor response and automated phase segmentation for the 12 mm Plywood Panel configuration

* **Caption:**
  > **Figure A5.** Sensor response and automated phase segmentation for the 12 mm Plywood Panel configuration. (a)–(f) as labelled in Figure A1.

* **Detailed Description:**
  * **Configuration:** Maximum solid timber cladding thickness tested ($12\text{ mm}$ plywood, $80\text{ mm}$ cavity depth).
  * **Observed Aerodynamics:** Convective velocity stabilizes at $v_{\text{air}} = 0.701\text{ m}\cdot\text{s}^{-1}$ (within $1\%$ of the standard panel).
  * **Thermal Response:** Increased solid wood thickness further dampens conduction, dropping backwall temperatures to $\text{STBI} = 35.0^{\circ}\text{C}$ ($t_{\text{plateau}} = 1.35\text{ h}$). Convective heat extraction remains elevated at $\dot{Q}_{\text{air}} = 123.0\text{ W}$ with $\Delta T_{\text{cavity}} = 8.1^{\circ}\text{C}$.

---

### Figure A6. Sensor response and automated phase segmentation for the High-Albedo Coated Panel (Trial 1)

* **Caption:**
  > **Figure A6.** Sensor response and automated phase segmentation for the High-Albedo Coated Panel (Trial 1). (a)–(f) as labelled in Figure A1.

* **Detailed Description:**
  * **Configuration:** Standard $5.5\text{ mm}$ panel coated with four layers of solar-reflective paint (Arcareflect 1198).
  * **Observed Aerodynamics:** Generates steady chimney airflow ($v_{\text{air}} = 0.691\text{ m}\cdot\text{s}^{-1}$) with $\Delta T_{\text{cavity}} = 7.3^{\circ}\text{C}$.
  * **Thermal Response:** The high solar reflectance limits skin heat absorption, moderating backwall temperature to $\text{STBI} = 37.5^{\circ}\text{C}$ ($t_{\text{plateau}} = 1.04\text{ h}$) while transporting $\dot{Q}_{\text{air}} = 109.5\text{ W}$ through natural ventilation.

---

### Figure A7. Sensor response and automated phase segmentation for the High-Albedo Coated Panel (Trial 2)

* **Caption:**
  > **Figure A7.** Sensor response and automated phase segmentation for the High-Albedo Coated Panel (Trial 2). (a)–(f) as labelled in Figure A1. Validation run evaluating measurement repeatability for surface temperatures, cavity gradients, and convective air velocity.

* **Detailed Description:**
  * **Configuration:** Independent replicate of the four-layer high-albedo coating under identical irradiance conditions ($772\text{ W}\cdot\text{m}^{-2}$).
  * **Observations:** Confirms empirical repeatability and precision of the automated Kneedle segmentation algorithm. Transient inflection times, plateau surface temperatures, and convective velocity trajectories match Trial 1 within experimental uncertainty limits.

---

### Figure A8. Sensor response and automated phase segmentation for the CryoPaint® Coated Panel (Trial 1)

* **Caption:**
  > **Figure A8.** Sensor response and automated phase segmentation for the CryoPaint® Coated Panel (Trial 1). (a)–(f) as labelled in Figure A1. Panel under three layers of CryoPaint® coating.

* **Detailed Description:**
  * **Configuration:** Standard $5.5\text{ mm}$ panel treated with three layers of daytime passive radiative cooling paint (CryoPaint®, Cryo X Co.).
  * **Observed Aerodynamics:** Induces chimney airflow at $v_{\text{air}} = 0.721\text{ m}\cdot\text{s}^{-1}$ alongside a vertical thermal gradient of $\Delta T_{\text{cavity}} = 8.1^{\circ}\text{C}$.
  * **Thermal Response:** High infrared emittance and solar reflectance reduce backwall surface heating to $\text{STBI} = 36.3^{\circ}\text{C}$ with rapid stabilization ($t_{\text{plateau}} = 0.97\text{ h}$). Convective evacuation extracts $\dot{Q}_{\text{air}} = 126.4\text{ W}$ ($+13.9\%$ greater than the uncoated standard panel).

---

### Figure A9. Sensor response and automated phase segmentation for the CryoPaint® Coated Panel (Trial 2 / Replicate)

* **Caption:**
  > **Figure A9.** Sensor response and automated phase segmentation for the CryoPaint® Coated Panel (Trial 2 / replicate). (a)–(f) as labelled in Figure A1. Panel under three layers of CryoPaint® coating. Validation run evaluating measurement repeatability for surface temperatures, cavity gradients, and convective air velocity.

* **Detailed Description:**
  * **Configuration:** Independent replicate run of the three-layer CryoPaint® assembly under controlled irradiance ($787\text{ W}\cdot\text{m}^{-2}$).
  * **Observations:** Demonstrates high experimental repeatability across surface thermocouples (STBB, STBI, STFI) and cavity probes ($T_{\text{top}}$, $T_{\text{bottom}}$), validating the rapid plateau attainment and steady-state cooling capacity observed in Trial 1.

---

## 4. Summary of Quasi-Steady-State Plateau Metrics (Table 5)

Values represent average measurements ($n=1$) recorded during the quasi-steady-state plateau phase across all rectangular shaft configurations:

| Figure | Configuration | $\Delta T_{\text{cavity}}\ (^{\circ}\text{C})$ | $v_{\text{air}}\ (\text{m}\cdot\text{s}^{-1})$ | $\dot{Q}_{\text{air}}\ (\text{W})$ | $\text{STBI}\ (^{\circ}\text{C})$ | $t_{\text{plateau}}\ (\text{h})$ | Irradiance $(\text{W}\cdot\text{m}^{-2})$ |
| :---: | :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **A1** | Negative Control (Sealed) | $0.6$ | $0.452$ | $5.9$ | $44.3$ | $1.20$ | $800$ |
| **A2** | Standard Panel ($5.5\text{ mm}$) | $7.2$ | $0.707$ | $111.0$ | $39.8$ | $0.96$ | $778$ |
| **A3** | Deep Cavity ($160\text{ mm}$) | $7.4$ | $0.789$ | $254.8$ | $33.9$ | $1.77$ | $774$ |
| **A4** | 9 mm Plywood Panel | $9.3$ | $0.714$ | $143.4$ | $37.9$ | $1.43$ | $820$ |
| **A5** | 12 mm Plywood Panel | $8.1$ | $0.701$ | $123.0$ | $35.0$ | $1.35$ | $804$ |
| **A6–A7**| High-Albedo Coated Panel | $7.3$ | $0.691$ | $109.5$ | $37.5$ | $1.04$ | $772$ |
| **A8–A9**| CryoPaint® Coated Panel | $8.1$ | $0.721$ | $126.4$ | $36.3$ | $0.97$ | $787$ |

---

## 5. Governing Thermodynamic Formulas

* **Vertical Air Temperature Gradient:**
  $$\Delta T_{\text{cavity}} = T_{\text{top}} - T_{\text{bottom}}$$
  Where $T_{\text{top}}$ and $T_{\text{bottom}}$ are the air temperatures ($^{\circ}\text{C}$) measured near the exhaust and intake apertures.

* **Cavity Air Mass Flow Rate:**
  $$\dot{m}_{\text{air}} = v_{\text{air}} \cdot A_{\text{cav}} \cdot \rho_{\text{air}}$$
  Where $v_{\text{air}}$ is the measured upper aperture airspeed ($\text{m}\cdot\text{s}^{-1}$), $A_{\text{cav}}$ is the channel cross-sectional area ($\text{m}^{2}$), and $\rho_{\text{air}}$ is the temperature-dependent density of air ($\text{kg}\cdot\text{m}^{-3}$).

* **Sensible Heat Transport Rate:**
  $$\dot{Q}_{\text{air}} = \dot{m}_{\text{air}} \cdot c_p \cdot \Delta T_{\text{cavity}}$$
  Where $\dot{Q}_{\text{air}}$ is the rate of heat removed by natural convection ($\text{W}$), and $c_p$ is the specific heat capacity of air ($1005\text{ J}\cdot\text{kg}^{-1}\cdot\text{K}^{-1}$).