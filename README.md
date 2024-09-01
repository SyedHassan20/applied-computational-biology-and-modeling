## **MRI Signal Processing and Image Quality Modeling** 

This notebook provides a comprehensive exploration of the physical principles and computational techniques underlying Magnetic Resonance Imaging (MRI). The project delves into several key aspects:

1. **Larmor Equation and Signal Processing:** The foundational physics behind MRI, including the Larmor equation, is explored in detail. The project models the precession of hydrogen atoms in a magnetic field, visualizing how the MRI signal decays over time due to free induction decay (FID).

2. **Magnetic Field Strength and Image Quality:** The relationship between magnetic field strength and MRI image quality is analyzed using a sigmoid model. The project also investigates how increasing the magnetic field strength can improve the signal-to-noise ratio (SNR) and contrast in MRI images but with diminishing returns as field strength increases.

3. **Monte Carlo Simulations:** To understand the variability and uncertainty in MRI imaging, Monte Carlo simulations are used to model the effect of noise on image quality. The simulations help elucidate how noise impacts the correlation between signal strength and image quality.

4. **Application to Medical Imaging:** The findings are contextualized within real-world MRI applications, with discussions on how these models can be used to optimize MRI settings for better diagnostic accuracy.
<br>

## **TSP and Disease Modeling** 

This repository contains a Jupyter Notebook focused on disease modeling using the Susceptible-Infectious-Recovered (SIR) model, a fundamental epidemiological model. The notebook provides a comprehensive analysis and simulation of disease spread, with the following technical highlights:

**Key Features:**
**SIR Model Implementation:** The notebook implements the SIR model using differential equations, simulating the dynamics of disease transmission within a population. The model includes equations for the rates of change of susceptible, infectious, and recovered individuals over time.

**Extended SIR Models:** Modifications to the basic SIR model to account for additional real-world factors such as:

**Vaccination Strategies:** Incorporating vaccination rates and their impact on disease spread.
**Antibiotic Resistance:** Modeling the effects of antibiotic use and the emergence of resistance.
**Population Susceptibility:** Addressing variability in susceptibility among different age groups (e.g., children, adults, elderly).
**Numerical Simulation and Visualization:** Numerical methods are employed to solve the differential equations, and the results are visualized to demonstrate the model's predictions over time.
