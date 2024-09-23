# ⚙️ **8051 Stepper Motor Interfacing**


<p align="center">
  <img src="https://github.com/gmostofabd/8051-Stepper-Motor/blob/cacac887a3c99781699d2d5544bdee57e883a349/assets/images/STEPPER_8051_Ckt.png" alt="AT89C51 Calculator" width="70%">
</p>

This repository demonstrates how to interface a stepper motor with the 8051 microcontroller using the **ULN2003** driver to handle the extra current required to run the motor. The project includes complete assembly code, Proteus simulation files, and documentation, along with screenshots and photos from testing.

## 📦 **Project Overview**
The project showcases the integration of a stepper motor with the **AT89C51** microcontroller, part of the 8051 family. The stepper motor is driven via the **ULN2003** Darlington transistor array, which provides the necessary current amplification to drive the motor efficiently. The Proteus simulation files enable you to visualize and test the functionality before implementing it on hardware.

### **Key Features:**
- **Stepper Motor Control**: Smooth, precise motor control using the 8051 microcontroller.
- **ULN2003 Driver**: Utilized to supply the necessary current for stepper motor operation.
- **Proteus Simulation**: Includes simulation files for stepper motor interfacing with an 8051 MCU.
- **Test Results**: Screenshots and photos from actual tests provide insights into the project's performance.

## 🔧 **Hardware Components**
- **AT89C51 Microcontroller**: Manages stepper motor control signals.
- **ULN2003**: Handles motor driving by amplifying current from the microcontroller.
- **Stepper Motor**: The primary motor used in the interfacing.
- **Power Supply**: Provides the necessary voltage and current for the system.

## 🖥️ **Simulation & Testing**
This project was simulated using **Proteus Design Suite** to verify the stepper motor's behavior and control before real-world implementation. The repository includes:
- Assembly code for controlling the stepper motor.
- Proteus simulation file showing motor operation.
- Screenshots and photos taken during the testing phase.

---

### 🚀 **Steps to Run the Project:**
1. **Clone this repository**:
   ```bash
   git clone https://github.com/yourusername/8051_Stepper_Motor_Interfacing.git
   ```
2. **Open the Proteus Simulation**: 
   Load the provided simulation file in **Proteus Design Suite** and run it to observe the motor's behavior.
3. **Compile and Upload the Code**:
   Use **MIDE-51** or any other 8051-compatible IDE to compile the assembly code and generate the HEX file.
4. **Test on Hardware**:
   After programming the microcontroller, assemble the circuit with the stepper motor and ULN2003, and power it on to observe real-time results.

---

## 📄 **Included Files:**
- **Assembly Code**: The code to drive the stepper motor using the 8051 microcontroller.
- **Proteus Simulation Files**: Pre-built simulation to test and visualize the circuit.
- **HEX File**: Ready-to-upload HEX code for the microcontroller.
- **Screenshots & Photos**: Visual proof of successful testing on both Proteus and hardware.

---
