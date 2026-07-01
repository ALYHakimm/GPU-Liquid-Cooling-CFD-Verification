# CAAF System: CFD & Sustainability Analysis

This repository contains the Python script and raw Ansys Fluent nodal data used to verify the thermodynamic efficiency and environmental impact of the CAAF liquid cooling system.

## 1. Exergetic Reliability Factor (ERF)
The script processes the exported `gpu_temperatures.csv` to calculate the ERF, ensuring thermal stability across all 8 GPUs under a 3200 W continuous thermal load.

## 2. Carbon Footprint Reduction
Based on the extracted coolant outlet temperature (334.8 K) obtained from the CFD simulation, the script calculates the energy recovery and subsequent $CO_2$ emission savings achieved by the CAAF system compared to traditional air cooling.

### **Automated Calculation Results:**
* **Baseline Emissions (Air Cooling):** 10,101 kg CO2/year
* **CAAF Emissions (Liquid Cooling):** 1,894 kg CO2/year
* **Total Environmental Savings:** **8,207 kg CO2/year**

![Carbon Footprint Comparison](CAAF_Carbon_Footprint_Comparison.png)
