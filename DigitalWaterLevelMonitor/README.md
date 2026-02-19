# Digital Water Level Monitoring System

Designed a digital logic-based water level monitoring system for a nuclear power plant spent fuel pool model.

The system determines the highest valid detected water level using four discrete sensor inputs and drives a 7-segment display to indicate level or error status.


## System Overview

Four water-level sensors represent discrete heights:

- 10 ft
- 20 ft
- 30 ft
- 40 ft

Each sensor outputs a logic HIGH (1) when water is present at that level.

The circuit evaluates the highest valid active level and outputs:

- 0 → No water detected
- 1 → 10 ft
- 2 → 20 ft
- 3 → 30 ft
- 4 → 40 ft
- E → Error condition


## Error Detection Logic

An error condition is triggered if:

- A higher-level sensor is active while a lower-level sensor is inactive  
  (Example: 40 ft active but 20 ft inactive)

This indicates invalid physical behavior and results in displaying **E** on the 7-segment display.


## System Capabilities

- Highest-level detection logic
- Invalid-state detection
- Combinational logic implementation
- 7-segment display control
- Structured logic validation in Logisim


## Display Implementation

The 7-segment display is driven directly from combinational logic outputs.

Example segment mapping:

- Displaying "4" (40 ft): segments 0, 1, 3, and 6 illuminated
- Error display: segments 0, 1, 2, 4, and 5 illuminated


## Engineering Focus

- Combinational logic design
- Priority encoding
- Error-state handling
- Hardware-oriented digital implementation
- Deterministic logic behavior


## Tools Used

- Logisim digital circuit modeling
- Structured gate-level implementation
- Simulation-based validation


This project demonstrates digital logic system design with built-in fault detection and structured display interfacing.
