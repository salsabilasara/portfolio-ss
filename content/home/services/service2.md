+++
date = "2024-11-24T12:00:00-00:00"
title = "Sugar Rocket"
+++

This project involved designing, fabricating, and testing a sugar rocket using solid rocket propellant. The primary objectives included propellant formulation, nozzle design, and trajectory modeling, culminating in a static test demonstration. The project aimed to develop practical engineering solutions for small-scale rocket propulsion systems, emphasizing efficiency, safety, and cost-effectiveness.
<!--more-->

[Download Certificate](/certificates/sugar_rocket_certificate.pdf)

## Design and Fabrication of a Sugar Rocket & Its Static Performance Testing
- **Course:** Capstone Design
- **Project Type:** Group Project
- **Grade Achieved:** A+
- **Institution:** Islamic University of Technology (IUT)
- **Department:** Mechanical and Production Engineering
- **Award:** 1st Prize in Capstone Design, Academic Year 2022-23

---

![Drawing of Sugar Rocket Assembly](../../../images/sugar_rocket.jpg)

*Caption: Capstone Design Project Showcasing*
---

### Propellant Composition
The propellant used was a sugar-based composite with the following components:
- **Fuel:** Sucrose (C12H22O11) – Non-toxic and readily available.
- **Oxidizer:** Potassium Nitrate (KNO3​) – Thermally stable and safe to handle.
- **Additive:** Iron Oxide (Fe2O3) – To enhance burn efficiency.

**Preparation Method:**  
The "Dissolving & Heating" method was selected for its low risk of ignition. Steps included dissolving the mixture in water, heating it to evaporate moisture, and molding it into rocket grains.

---

### Nozzle Design
The nozzle was modeled as a converging-diverging type. Simulations were conducted in ANSYS Fluent with the following conditions:
- **Inlet Pressure:** 4 MPa
- **Inlet Temperature:** 2500 K
- **Outlet Pressure:** Atmospheric (101325 Pa)

A hex-dominant mesh (6133 elements) ensured accuracy. The optimal nozzle outlet diameter of 144 mm achieved a maximum exhaust velocity of 2050 m/s. The final nozzle mass was 2.97 kg.

---

### Trajectory Modeling
The rocket's trajectory was modeled in MATLAB using classical mechanics equations. Key factors included thrust, drag, and gravitational acceleration, with data from OpenMotor for burn parameters.

- **Predicted maximum altitude (current design):** 307.8 meters
- **Predicted maximum altitude (optimized design):** 1210 meters

The MATLAB code generated time-based graphs for altitude, velocity, and acceleration.

---
### Drawing
Below is the drawing of the final sugar rocket assembly:

![Drawing of Sugar Rocket Assembly](../../../images/sugar_rocket_drawing.jpg)

*Caption: Sugar Rocket Assembly (all dimensions in mm)*

### Static Test Results
The static test, performed on **December 1, 2023**, yielded the following results:
- **Effective Burn Time:** 7.2 seconds
- **Peak Thrust:** 7.1 kg-wt
- **Average Thrust:** 5.6 kg-wt
- **Total Delivered Impulse:** 395.54 Ns
- **Rocket Assembly Mass:** 3.4 kg (optimized to 1.4 kg for launch)
- **Thrust-to-weight Ratio:**
    - Current: 2.088 (Peak), 1.647 (Average)
    - Optimized: 5.071 (Peak), 4 (Average)

---

### Significance
Static testing demonstrated cost-effective propulsion analysis without a full-scale launch. This was the fourth successful burn of the assembly, paving the way for further optimization and study.

---
![Drawing of Sugar Rocket Assembly](../../../images/sugar_rocket_prize.jpg)

*Caption: Capstone Design Project Showcasing 1st prize*

### Acknowledgment
This project was conducted under the supervision of esteemed professors from the **Mechanical and Production Engineering Department** at the **Islamic University of Technology (IUT).**

---

