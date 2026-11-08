# AMR Condition Monitoring - Digital Twin

A ROS 2 and Gazebo-based Digital Twin framework for an Autonomous Mobile Robot (AMR), integrating real-time robot communication, virtual simulation, condition monitoring and intelligent predictive maintenance.

## Project Overview

This project aims to develop a synchronized digital representation of an Elephant Robotics myAGV 2023 mobile robot.

The framework establishes communication between a physical AMR and its virtual counterpart, enabling real-time data exchange, simulation synchronization, performance monitoring and future integration of edge AI-based condition monitoring.

## Objectives

- Develop a virtual AMR model using URDF/SDF.
- Implement a Gazebo-based digital twin.
- Establish TCP/IP communication between the physical robot and digital twin.
- Synchronize robot state and sensor information.
- Evaluate communication latency, update frequency and packet loss.
- Develop condition-monitoring capabilities.
- Explore edge AI integration for predictive maintenance.

## Hardware Platform

| Component | Description |
|---|---|
| Mobile robot | Elephant Robotics myAGV 2023 |
| Onboard computer | Raspberry Pi |
| Simulation workstation | Ubuntu 24.04 laptop |
| Sensors | Robot-integrated sensors |
| Communication | TCP/IP over local network |

## Software Stack

- Ubuntu 20.04 - Physical robot environment
- Ubuntu 24.04 - Simulation workstation
- ROS 2 Jazzy - Digital twin middleware
- Gazebo - 3D simulation
- RViz2 - Robot visualization
- Python / C++ - Application development
- TCP/IP - Robot-to-twin communication

## System Architecture

The proposed architecture consists of four primary layers:

1. Physical AMR: Real-world robot operation and sensor acquisition.
2. Communication Layer: TCP/IP-based data transmission.
3. Digital Twin: Virtual robot model and simulation synchronization.
4. Monitoring Layer: Performance evaluation and condition assessment.

## Repository Structure

- `robot_ws/` - Physical robot integration
- `digital_twin_ws/` - Digital twin simulation
- `communication/` - TCP/IP communication modules
- `monitoring/` - Condition monitoring
- `docs/` - Technical documentation
- `results/` - Experimental results and visualizations

## Performance Evaluation

The following metrics will be investigated:

- End-to-end communication latency
- Digital twin update frequency (Hz)
- Packet loss ratio
- Data synchronization accuracy
- Network throughput
- Simulation responsiveness

## Development Roadmap

- [ ] Establish the physical robot communication interface.
- [ ] Develop and validate the virtual AMR model.
- [ ] Integrate Gazebo simulation.
- [ ] Establish TCP/IP communication.
- [ ] Implement real-time digital twin synchronization.
- [ ] Benchmark communication performance.
- [ ] Integrate condition-monitoring algorithms.
- [ ] Explore edge AI-based predictive maintenance.

## Research Direction

The long-term objective is to investigate the integration of Digital Twin technology, Industrial AI and edge intelligence for intelligent condition monitoring of autonomous mobile robots.

## License

This project is intended for academic, educational and research purposes.
