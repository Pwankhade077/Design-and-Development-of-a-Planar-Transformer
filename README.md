# Design-and-Development-of-a-Planar-Transformer

## Project Report
[View Full Report](./li_dab.pdf)

This project presents the design and validation of a 200W planar transformer for a Dual Active Bridge (DAB) converter operating at 50 kHz. The objective is to achieve controlled power transfer using leakage inductance while maintaining high magnetic coupling and low losses.

## Project Overview

- Input Voltage: 48 V  
- Output Voltage: 107 V  
- Output Power: 200 W  
- Switching Frequency: 50 kHz  

## Transformer Design

- Magnetizing Inductance (Lm): 448.4 µH  
- Leakage Inductance (Llk): 27.2 µH  
- Coupling Coefficient: ~0.993  
- Turns Ratio: 2.24  
- Core Material: N87 Ferrite (E64/10/50)  

## Design Objectives

- Controlled power transfer using leakage inductance  
- High magnetic coupling  
- Reduction of core and copper losses  
- Validation using multiphysics simulations  

## Validation and Analysis

The design was validated using different simulation tools:

- Maxwell 3D for magnetic field analysis  
- Icepak for thermal analysis (maximum temperature around 59°C)  
- Simplorer for system-level validation of the DAB converter  

## Results

- Achieved 200W power transfer  
- Output validated at approximately 107V and 1.87A  
- Transformer loss around 3.6 W  
- Estimated efficiency close to 98%  

## Key Insight

The leakage inductance (27.2 µH) is designed to control power transfer in the DAB converter using phase-shift control.

## Files

- Full report available in this repository
