# Electronic Circuit Systems

A collection of analog and digital electronic systems designed, simulated, and validated through both SPICE modeling and physical hardware implementation.

These projects demonstrate practical circuit design, finite-state control logic, signal amplification, and system-level electrical validation.

## Project Portfolio

### 1️⃣ Motor Control Finite-State Machine (FSM)

Designed a safety-driven motor engagement system for control rod positioning in a nuclear reactor model.

**System Features**
- Finite-state machine implementation  
- Directional motor control (UP / DOWN)  
- Safety interlocks to prevent simultaneous actuation  
- Emergency stop (ESTOP) priority override  
- Position detection via TOP and BOTTOM limit switches  

**Engineering Focus**
- Safe control logic design  
- State prioritization  
- Fault condition handling  
- Deterministic hardware behavior  

This project demonstrates structured digital control design applicable to industrial automation and embedded safety systems.

---

### 2️⃣ Multi-Stage Analog Amplifier

Designed and validated a discrete BJT multi-stage amplifier to deliver ≥1 mW into an 820Ω load.

**Design Specifications**
- Input signal: 10 mV amplitude  
- Source resistance: 8 kΩ  
- DC supply: 18 V  
- Active components: 2 × 2N3904 BJTs  
- Low-frequency cutoff (3dB): 1 kHz ±2%  
- Gain slope: 20 dB/decade below 1 kHz  

**Validation**
- LTSpice simulation for frequency response and gain analysis  
- Transfer function characterization  
- Physical breadboard implementation  
- Symmetric waveform verification  

This project highlights analog signal amplification, frequency response analysis, and real-world hardware validation.

---

### 3️⃣ Digital Water Level Monitoring System

Designed a digital logic-based water level detection system for a nuclear power plant spent fuel pool model.

**System Capabilities**
- Four discrete water-level sensors (10', 20', 30', 40')  
- Highest-level detection logic  
- Error detection for inconsistent sensor states  
- 7-segment display output  
- Fault indication via error code display  

**Engineering Focus**
- Combinational logic design  
- Error-state handling  
- Hardware display interfacing  

This project demonstrates digital logic implementation and structured system validation.

---

## Tools & Platforms

- LTSpice simulation  
- Logisim digital circuit modeling  
- Breadboard hardware implementation  
- Discrete transistor-based design  
- Analog frequency response analysis  

## Engineering Themes Demonstrated

- Analog circuit design  
- Digital logic systems  
- Finite-state machine implementation  
- Safety-priority control systems  
- Hardware validation and testing  
- Simulation-to-physical implementation workflow  


