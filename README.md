# Simulation-Based Performance Comparison of Coconut-Shell-Derived Activated Carbon Supercapacitors

## Overview

This project investigates the electrochemical behaviour of coconut-shell-derived activated carbon (CSAC) as an electrode material for sustainable energy storage applications.

The study focuses on two supercapacitor configurations:

- Flat-type supercapacitor
- Cylindrical supercapacitor

The objective is to investigate how electrode geometry influences charge storage, voltage distribution, energy density, and electrochemical performance.

Computational modelling is used to analyse the internal behaviour of the supercapacitor structures and understand the relationship between electrode architecture and energy storage performance.

## Research Objectives

- Investigate coconut-shell-derived activated carbon as a sustainable electrode material.
- Develop flat-type and cylindrical supercapacitor models.
- Analyse voltage and energy density distributions.
- Study electrode potential and current density.
- Compare the influence of electrode geometry on electrochemical behaviour.
- Explore the potential of biomass-derived carbon for sustainable energy storage.

## Simulation Methodology

The models represent three primary domains:

1. Anode
2. Electrolyte
3. Cathode

Material properties such as electrode conductivity, electrolyte conductivity, porosity, specific surface area, and double-layer capacitance are used as model inputs.

The study examines electrochemical behaviour through:

- Galvanostatic Charge–Discharge (GCD) analysis
- Electrochemical Impedance Spectroscopy (EIS)
- Transient voltage analysis
- Effective capacitance estimation
- Stored energy calculation
- Voltage and energy density mapping
- Electric potential and current density distribution

## Model Configurations

### 1. Flat-Type Supercapacitor

A two-dimensional layered geometry consisting of anode, electrolyte, and cathode regions.

The model investigates:
- Transient voltage response.
- Effective capacitance.
- Stored energy.
- Two-dimensional voltage distribution.
- Energy density distribution.

### 2. Cylindrical Supercapacitor

An axisymmetric cylindrical electrode configuration designed to investigate radial electrochemical behaviour.

The model investigates:
- Potential distribution across electrode regions.
- Current density distribution.
- Voltage and energy density maps.
- Charge transport behaviour.
- Three-dimensional field visualisation.

## Tools and Technologies

| Technology | Application |
|---|---|
| MATLAB | Numerical modelling and post-processing |
| MATLAB PDE Toolbox | Transient PDE-based simulation |
| COMSOL Multiphysics | Electrochemical modelling as described in the research paper |
| Finite Element Analysis | Spatial discretisation and field analysis |
| Electrochemical Modelling | Charge storage and transport analysis |

Note: The MATLAB PDE implementations and COMSOL methodology are documented separately. The corresponding native model files should be added when available.

## Research Findings

The research paper reports that the cylindrical configuration provides higher volumetric capacitance and improved simulated energy and power density compared with the flat-type configuration.

The study also discusses the potential advantages of coconut-shell-derived activated carbon, including sustainability, waste utilisation, and its potential as an alternative to conventional activated carbon.

These findings are simulation-based and should be interpreted within the assumptions and material parameters of the models.

## Repository Structure

```text
MATLAB/
    flat_type/
    cylindrical/

COMSOL/
    flat_type/
    cylindrical/

Results/
    geometry/
    mesh/
    voltage_distribution/
    energy_density/
    electrochemical_analysis/

Research_Paper/
```

## Applications

Potential applications of the investigated technology include:

- Electric vehicle energy storage.
- Battery–supercapacitor hybrid systems.
- Grid energy storage and stabilisation.
- Renewable energy storage.
- High-power electronic applications.
- Sustainable energy storage technologies.

## Future Scope

- Experimental fabrication and validation of CSAC electrodes.
- Investigation of different activation methods.
- Optimisation of electrode porosity and thickness.
- Performance evaluation under different electrolyte conditions.
- Improved electrochemical equivalent circuit modelling.
- Experimental comparison with commercial supercapacitors.

## Authors

**Visham Kumar V**  
**Jegadeesh S S**

Department of Electrical and Electronics Engineering  
Amrita School of Engineering, Coimbatore  
Amrita Vishwa Vidyapeetham, India

## Acknowledgement

This work was carried out as part of an academic research project with guidance and support from the Department of Electrical and Electronics Engineering, Amrita School of Engineering.

## Keywords

Supercapacitor | Coconut Shell Activated Carbon | Biomass-Derived Carbon | MATLAB | COMSOL | Electrochemical Modelling | Finite Element Analysis | Sustainable Energy Storage

---

*This repository is intended for academic, research, and educational purposes.*
