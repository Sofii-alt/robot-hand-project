# Robotic Hand (Class Project)
---
## Final Goal
The goal of this project is to design and build a 3D printed robotic hand controlled by a Raspberry Pi 5 and a motor.
For the class requirement, the system needs to demonstrate at least a basic gripping motion.
Whether the final version becomes a full hand or a simpler gripping mechanism depends on time, but the plan is to aim high and scale down only if needed.

## Design
I wanted to take inspiration from human hand mechanics. However, because of the limited materials, I had to scale the design down to 3 fingers to get a good enough grip. Due to time constraints, the current version has just 2 fingers, but I designed and printed the base with a ready-made place for the 3rd finger so it can be added later.


(Final finished picture of the hand (in progress ...))
<img width="1125" height="2000" alt="image" src="https://github.com/user-attachments/assets/a34948de-e49a-4d4a-a525-ef3eac0d03fa" />
<img width="982" height="393" alt="image" src="https://github.com/user-attachments/assets/20f2f0c8-f0d4-4ad5-994b-de9d1b138b9b" />
<img width="2048" height="1865" alt="image" src="https://github.com/user-attachments/assets/e7b48bea-b29e-4041-97b0-5de54ba50f04" />

## Project Ownership & Contributions
This project was developed as part of a school course. The hardware (motor, microcontroller, and Raspberry Pi 5 setup) and the foundational ROS2 open-source codebase were provided by the institution.
My original contributions include:
- Mechanical Design and 3D Modeling: I designed, 3D modeled, and printed the entire physical structure and gripper mechanism from scratch.
- Software Engineering: I took the raw ROS2 open-source templates and filled in, adapted, and fixed the code to make it work seamlessly with my specific hardware setup.


## Physical project stages
1. Concept Phase
Started with sketches on paper. Tested joint movement using a paper model to understand flexibility and range of motion.

2. 3D Modeling
Designed the fingers and palm in Fusion. Focus is on improving joint movement and stability.

3. Motor Integration
After printing the 3D parts, the motor system will be connected and controlled using the Raspberry Pi 5.

4. Testing and Improvements
The hand will be tested for grip strength and movement control. Adjustments will be made if needed.
Test vlog:
- Doesn't have the rubber bands that would coil the finger back upright, so the movement is uncontrolled and doesn't close properly. Also, the motor might not be strong enough for the gripper and rubber bands. If there's not enough tension in the string, the full motion of the finger isn't completed.
- But now the code works as intended.
- video of the first test: https://github.com/user-attachments/assets/e1b28ec2-4d8e-402b-80ff-45842b7e216e

5. Final version
(The gripper has been tested and now works nominaly well)
in progress ....

## Project Structure
- ` gripper-designs/ ` : All design versions
- ` motor-design/ `: Motor setup and integration (unfinished)
- ` timeline/ ` : Development progress

## Current Status
- Currently working on the testing phase. Got a new stronger motor. Will have to ajust the 3D desines
