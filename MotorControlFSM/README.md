# Motor Control Finite-State Machine (FSM)

Designed a safety-driven motor engagement system for control rod positioning in a nuclear reactor model.

This project implements a structured finite-state machine (FSM) to control directional motor actuation with strict safety interlocks and deterministic behavior.


## System Features

- Finite-state machine implementation  
- Directional motor control (UP / DOWN)  
- Safety interlocks preventing simultaneous motor activation  
- Emergency stop (ESTOP) priority override  
- Position detection via TOP and BOTTOM limit switches  
- Deterministic state transitions  


## System Inputs

- **DIRECTION**  
  - `1` → Insert control rods  
  - `0` → Remove control rods  

- **GO**  
  - Momentary activation command  

- **ESTOP**  
  - Emergency override input  

- **TOP**  
  - Indicates rods fully retracted  

- **BOTTOM**  
  - Indicates rods fully inserted  


## System Outputs

- **MOTOR_UP**  
- **MOTOR_DOWN**

Safety Constraint:  
`MOTOR_UP` and `MOTOR_DOWN` are never active simultaneously.


## Engineering Focus

- Finite-state control architecture  
- Safety-priority logic handling  
- Sequential and combinational logic integration  
- Fault-condition mitigation  
- Structured hardware-safe control sequencing  


## Tools & Implementation

- Logisim digital circuit modeling  
- Combinational and sequential circuit design  
- Structured test-case validation  
- State transition verification  


## Engineering Themes Demonstrated

- Industrial control logic design  
- Embedded-system safety concepts  
- Deterministic hardware behavior  
- System-level digital validation  
