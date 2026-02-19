# Multi-Stage BJT Amplifier

Designed and validated a discrete two-stage BJT amplifier to deliver ≥1 mW into an 820Ω load from a low-amplitude input source.

This project demonstrates analog signal amplification, frequency response shaping, and full simulation-to-hardware validation.


## Design Specifications

- Input signal amplitude: 10 mV  
- Source resistance (Rs): 8 kΩ  
- DC supply voltage: 18 V  
- Active components: 2 × 2N3904 BJTs  
- Load resistance: 820 Ω  
- Minimum output power: ≥1 mW  
- Low-frequency cutoff (3 dB): 1 kHz ±2%  
- Gain slope: 20 dB/decade below cutoff  


## Engineering Objectives

- Achieve sufficient voltage gain to drive an 820Ω load
- Maintain symmetric output waveform
- Implement predictable frequency roll-off
- Validate theoretical gain using simulation and physical testing


## Simulation

- LTSpice schematic modeling
- Frequency response analysis
- Transfer function characterization
- Gain verification in dB scale
- Low-frequency pole analysis


## Hardware Validation

- Physical breadboard implementation
- Biasing verification for both BJT stages
- Output waveform symmetry validation
- Real-world component tolerance considerations


## Engineering Themes Demonstrated

- Multi-stage analog amplification
- Transistor biasing and operating point design
- Frequency response shaping
- Simulation-to-physical validation workflow
- Discrete component design methodology
