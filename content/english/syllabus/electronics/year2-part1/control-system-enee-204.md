---
title: "Control System - BEI II/I Syllabus"
meta_title: "Syllabus: Control System (ENEE 204) - BEI Year 2 Part 1 | IOE Notes"
description: "Detailed syllabus for Control System (ENEE 204), a second year, first part subject in the IOE BEI program."
draft: false
image: "/images/syllabus/electronics-syllabus.jpg"
tags: ["BEI", "Electronics Engineering"]
subject: "Control System"
subject_code: "ENEE 204"
faculty: "Electronics, Communication and Information Engineering"
faculty-code: "BEI"
lecture: 3
tutorial: 1
practical: 1.5
year: 'II'
part: 'I'
---


### Course Objectives
The objective of this course is to provide foundational knowledge in control system analysis and design. It introduces essential concepts needed to understand and create control systems. Students will learn to model and analyze control mechanisms. The course emphasizes applying these principles to real-world physical processes.

---

### 1. Control System Background (2 hours)
- History of control system and its importance
- Control system: Characteristics and basic features, components and variables
- Types of control system and their comparison

---

### 2. Component Modeling (6 hours)
- Differential equation and transfer function notations
- Modeling of mechanical components: Mass, spring and damper
- Modeling of electrical components: Inductance, capacitance, resistance, DC and AC motor, transducers and operational amplifiers
- Electric circuit analogies: Force-voltage analogy and force-current analogy
- Linearized approximations of non-linear characteristics

---

### 3. System Transfer Function and Responses (10 hours)
- Combinations of components to physical systems
- Block diagram algebra and system reduction
- Signal flow graphs
- Time response analysis
  - Types of test signals: Impulse, step, ramp, parabolic
  - Time response analysis of first order system
  - Time response analysis of second order system
  - Transient response characteristics: Rise time, peak time, delay time, settling time and maximum overshoot
- Static error coefficients and steady state error
- P, PI, PD, PID controller and derivative feedback controller

---

### 4. Stability (4 hours)
- Introduction of stability and causes of instability
- Characteristic equation, root location and stability
- Setting loop gain using Routh-Hurwitz (R-H) criterion
- R-H stability criterion
- Relative stability from complex plane axis shifting

---

### 5. Root Locus Technique (6 hours)
- Introduction of root locus
- Relationship between root loci and time response of systems
- Rules for manual calculation and construction of root locus
- Stability concept from Root Locus

---

### 6. Frequency Response Techniques (8 hours)
- Frequency domain characterization of the system
- Relationship between real and complex frequency response
- Polar plot
- Stability analysis in frequency domain: Gain margin, phase margin
- Nyquist plot and criterion for stability analysis
- Polar plot and Nyquist plot
- Bode Plot: Significance of Bode plot, Magnitude and phase plot
- Stability analysis from Bode plot

---

### 7. Performance Specifications and Compensation Design (6 hours)
- Compensation technique and compensator
- Application of root locus and frequency response on control system design
- Lead, lag cascade compensation design
  - Root locus method
  - Bode plot method
- Concept of Lead-lag compensator

---

### 8. State Space Analysis (4 hours)
- Definition of state-space, state variables and state vector
- State space representation of electrical and mechanical system
- Conversion from state space to a transfer function
- Conversion from transfer function to state space
- State-transition matrix

---

### Tutorial (15 hours)
1. Modeling exercises of mechanical/electrical system and analogy
2. Block diagram model development and reduction, SFG exercise
3. Time response exercise of first order and second order system and steady state error and PID
4. RH criterion and relative stability numerical, root locus plot
5. Polar and Nyquist Plot, Bode plotting and stability analysis in frequency domain
6. Compensator design exercises from Root locus and Bode plot approach for lead and lag compensator
7. State space model development exercises from differential equation, transfer function model and vice versa and stability check

---

### Practical (22.5 hours)
1. To study open loop and closed mode for DC motor and familiarization with different components in DC motor control module.
2. To determine gain and transfer function of different control system components
3. To study effects of feedback on gain and time constant for closed loop speed control system and position control system
4. To determine frequency response of first order and second order system and to get transfer function
5. Simulation of closed loop speed control system and position control system and verification

---

### Final Examination
| Chapter | Hours | Marks distribution* |
|---------|-------|---------------------|
| 1       | 2     | 4                   |
| 2       | 6     | 8                   |
| 3       | 10    | 12                  |
| 4       | 4     | 4                   |
| 5       | 6     | 8                   |
| 6       | 8     | 12                  |
| 7       | 6     | 8                   |
| 8       | 3     | 4                   |
| **Total** | **45** | **60**             |

*There may be minor deviation in marks distribution.*

---

### References
1. Ogata, K. (2009). Modern Control Engineering (5th edition). Pearson
2. Gopal, M. (2009). Control Systems: Principles and Design (4th edition). Tata McGraw-Hill.
3. Kuo, B. C. (2015). Automatic Control System (9th edition). Willey India.
4. Nagrath, I. J., Gopal, M. (2021) Modern Control Engineering (7th edition) New Age International.
5. Hassan, S. (2013). Automatic Control System (Reprint 2013). Arihant.
