# Voice Control Car with Obstacle Avoiding

## Abstract
This project presents an Arduino-based autonomous robotic car capable of operating in three different modes: voice control, Bluetooth manual control, and automatic obstacle avoidance. The system integrates ultrasonic sensing, servo-based environmental scanning, and mobile-based voice commands to achieve reliable navigation without human intervention.

The project demonstrates practical applications in autonomous vehicles, service robots, and planetary exploration research.

---

## Objectives
- Develop a driver-free robotic vehicle
- Implement voice-based motion control
- Design an obstacle avoidance system using ultrasonic sensing
- Explore applications in smart vehicles and service robots
- Provide a foundation for future planetary rover research

---

## System Features
- Voice command navigation via Bluetooth
- Real-time obstacle detection and avoidance
- Manual control through Android application
- Servo-based directional scanning
- Modular and scalable design

---

## Hardware Components
| Component | Quantity |
|--------|---------|
| Arduino UNO | 1 |
| L293D Motor Driver | 1 |
| Ultrasonic Sensor | 1 |
| Bluetooth Module (HC-05/HC-06) | 1 |
| Servo Motor | 1 |
| DC Gear Motors | 4 |
| Robot Wheels | 4 |
| Li-ion Batteries | 2 |
| Battery Holder | 1 |
| Jumper Wires | As required |
| Chassis (Foam Board/Cardboard) | 1 |

---

## Software Requirements
- Arduino IDE 2.0.3
- Windows OS
- Arduino Bluetooth RC Car (Android)
- Arduino Bluetooth Control (Android)

---

## Control Modes

### 1. Obstacle Avoidance Mode
The ultrasonic sensor continuously measures distance. If an obstacle is detected within a predefined threshold, the robot stops, scans left and right using a servo motor, and chooses the safest path.

### 2. Bluetooth Manual Control
The robot receives directional commands from a smartphone application via Bluetooth communication.

### 3. Voice Control Mode
Predefined voice commands are converted into character signals and transmitted to the Arduino via Bluetooth.

#### Supported Commands
| Voice Command | Action |
|-------------|-------|
| Go | Move Forward |
| Back | Move Backward |
| Left | Turn Left |
| Right | Turn Right |
| Stop | Halt Movement |

---

## Circuit Diagram
The complete circuit diagram is available in the `hardware/` directory.

---

## Implementation Steps
1. Design and assemble the robot chassis
2. Connect hardware components based on the circuit diagram
3. Develop and upload Arduino firmware
4. Configure Bluetooth and mobile applications
5. Test all three operational modes
6. Perform calibration and optimization

---

## Budget Summary
A detailed budget breakdown is provided in `documentation/budget_proposal.md`.

---

## Applications
- Autonomous vehicle research
- Service robots (restaurants, hospitals)
- Smart transportation systems
- Planetary exploration rovers
- Educational robotics platforms

---

## Future Enhancements
- AI-based voice recognition
- Camera-based obstacle detection
- GPS navigation
- IoT-based remote monitoring

---

## Author
**Efat Khan**  
Department of Engineering  
Bangladesh

---

## License
This project is released under the MIT License for educational and research purposes.
