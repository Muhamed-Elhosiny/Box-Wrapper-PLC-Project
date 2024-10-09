# Box-Wrapper-PLC-Project
PLC-based automation system for a box wrapping machine

# Box Wrapper Automation Project

This project is an automation solution for a **Box Wrapper Machine** using a **Siemens S7-1200 PLC**. It includes PLC programming, motor control, and sensor integration to automate the process of wrapping boxes.

## Project Overview

The Box Wrapper is designed to:
- Move the wrapping film up and down using a motor.
- Rotate the box during wrapping.
- Stop at the appropriate top and bottom limits using limit switches.
- Control the speed and motor actions via a Variable Frequency Drive (VFD).

### Components Used:
1. **PLC**: Siemens S7-1200
2. **VFD**: 0.37kW and 0.55kW
3. **Sensors**: 
   - High Limit Switch (NO)
   - Low Limit Switch (NO)
   - Proximity Sensor for counting rotations
4. **Software**: TIA Portal with simulation using PLCSim.

## System Diagram
(Include any system diagrams, wiring diagrams, and control logic here)

## How It Works
The wrapping process is fully automated, with:
- **Up/Down Motor** controlled by the PLC.
- **Limit switches** that stop the motor when the wrapping arm reaches its limits.
- **Proximity sensors** to monitor wrapping speed and rotation count.

### Logic Implementation
The PLC controls the system using ladder logic with the following key functions:
- **Motor Control**: The VFD drives the motors, which are started and stopped by PLC inputs from the sensors.
- **Safety Interlocks**: Limit switches prevent over-extension of the wrapping arm.

### Simulation and Testing
- The project was first simulated in TIA Portal using PLCSim to ensure proper motor control and sensor integration.
- (Include screenshots or code snippets of your PLC simulation setup)

### Installation and Deployment
1. Install the Siemens S7-1200 PLC.
2. Connect the VFD to control the motors.
3. Wire the limit switches and sensors to the PLC.
4. Download the PLC program (located in the `/code` folder).
5. Monitor and control the system via HMI (optional).

### Future Improvements
- Adding an HMI for manual control and monitoring.
- Improving the wrapping material tension control.

## Folder Structure
- `/code`: Contains the PLC programming files (Ladder Logic in TIA Portal format).
- `/docs`: Contains all the documentation and diagrams.
- `/simulations`: Files used for simulation testing in PLCSim.

## Contact
If you have any questions about this project, feel free to contact me at [YourEmail@example.com](mailto:YourEmail@example.com).

