# Traffic Light Control System 🚦

Welcome to the **Traffic Light Control System Project**! This project serves as a simulation of how traffic lights operate, designed as a **final exam project** for my college course in **Computer Architecture**. The system was built using **Logisim**, focusing on logic gates, flip-flops, and timers to create an accurate and functional traffic light sequence.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [How It Works](#how-it-works)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Challenges](#challenges)
- [Conclusion](#conclusion)

---

## Overview

The **Traffic Light Control System** is a digital circuit designed to simulate the behavior of traffic lights at an intersection. Using **Logisim**, this project demonstrates how various components such as timers, counters, and logic gates work together to control the flow of traffic effectively.

This project was created as part of a college **Computer Architecture** course and serves as an excellent example of applying theoretical knowledge in a practical scenario.

---

## Features

- **Sequential Traffic Light Timing**: 
  - Red, Yellow, and Green lights follow a proper sequence.
  - Configurable timing for each light.

- **Pedestrian Crossing Mode**:
  - Allows simulation of pedestrian signals in sync with the main traffic lights.

- **Emergency Stop Feature**:
  - Simulates an override for emergency vehicles, turning all lights red temporarily.

---

## How It Works

The circuit is built using **Logisim** and operates based on:

1. **Counters**:
   - Count clock pulses to determine the duration of each light (e.g., Red = 10 seconds, Yellow = 3 seconds, Green = 7 seconds).

2. **Logic Gates**:
   - Control transitions between lights based on counter outputs.

3. **Flip-Flops**:
   - Maintain state (e.g., which light is active) and ensure proper synchronization.

4. **Clock Pulses**:
   - Provide timing intervals for the counters and flip-flops.

### Traffic Light Sequence:
- **Red Light**: Stops all traffic for 10 seconds.
- **Green Light**: Allows traffic to move for 7 seconds.
- **Yellow Light**: Warns drivers for 3 seconds before transitioning back to red.

---

## Technologies Used

- **Logisim**: Primary tool for designing and simulating the circuit.
- **Logic Gates**: AND, OR, NOT, etc., for decision-making.
- **Flip-Flops**: To maintain and toggle states.
- **Counters**: To manage timing for lights.
- **Clock Signal**: To drive the sequential behavior.

---

## Usage

1. **Clone or Download** the project files.
2. Open the `.circ` file in **Logisim**.
3. Simulate the circuit by running the clock.
4. Observe the traffic light sequence and test features like the pedestrian mode or emergency stop.

---

## Challenges

- **Timing Synchronization**:
  - Ensuring all lights transition smoothly without overlap.
- **Flip-Flop States**:
  - Debugging issues with state retention during light changes.
- **Realism**:
  - Balancing theoretical timing with real-world traffic scenarios.

---

## Conclusion

This project was a great way to explore the practical application of computer architecture concepts. From designing logic gates to implementing counters and flip-flops, the **Traffic Light Control System** highlights how digital circuits can solve real-world problems.
thanks for checking !
