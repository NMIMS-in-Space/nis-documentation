# NMIMS Robotics Testbed-1 (NRT-1)

The versatility of MSMAs/FSMAs makes them unique for our use-case. General-purpose Shape Memory Alloys (SMAs) are already used in multiple space applications; proving their worthiness & efficiency over classical sensors & actuators time & time again. Proposed MSMAs allow a new breed of space equipment — imagine a chassis that can change its shape, act as a sensor & does not require any real actuator for movement.

With our research, we wish to bring new materials, soft robotics & underactuated robotics and all their benefits in terms of efficiency, cost-effectiveness & versatility to the New Space revolution in India & to ISRO. Further down the line, we also wish to research upcoming soft-robotics applications & attempt to retrofit the same in space-based applications. Based on the results we provide, we also expect future space missions to have improved efficiency, longer fatigue life, and lower costs on switching to MSMAs instead of traditional sensors (like magnetometers) or actuators (like a BLDC) or structural components (like cable nets used for deployment in Cubesats).

## The Opportunity

### Satellize - SpaceShare

Satellize (previously exceed space) is India's first private company in space. After succesfully launching two saatellites in orbit, in 2019 Satellite presented the Spaceshare program. A joint venture of Satellize and ISRO, Spaceshare provides University students, college students and NGOs an opportunity to launch their payloads in space for free. Upto 10 payloads are selected to be integrated onboard the Polar Satellite Launch Vehicle.
 

### 4th stage of PSLV (PS4)

PSLV, known as the workhouse of ISRO, boasts numerous successful multi-satellite deployment as a rideshare service for small satellites. The fourth stage is the uppermost stage of the PSLV is capable of its own power generation with an array of solar cells. The spaceshare module is intended to be a static part of this phase, drawing energy from the solar cells and communicating with the Satellize HQ. 

### Technical Requirements

specific dimensions; restrictions on sensors/ components
*Conference Plan Table*

## The Experiment

### The Idea

#### Smart materials?

With the increasing interest in Smart Materials and their applications, reasearchers have been gravitated towards materials that can pose as a possible substitute for alloys used in payloads. Materials that can achieve similar results with compact designs, lighter weight and modular structures are prefered. With these considerations Magnetostrictive materials prove as a valid alternative. Terfenol-D, composed of Terbium, Dysprosium and Iron, exhibits the capability of changing its shape and/or dimension during the process of magnetization. This opens up oppotunities of smaller satellites that can expand, dilate or adapt.

#### Terfenol-D

Terfenol D exhibits the highest magnetostriction out of any alloy, with upto 0.002 m/m at saturation. They have shown promising results when used for low frequency acoustic devices.
Space Robotics/ COTS for space usage
Designing better components for space
Design
The payload had to be designed to test as many material properties as possible while considering the general limitations of an object launched in space, such as restrictions of potentially hazardous materials, as well as the oppotunities provided to us by the spaceshare module, such as maximum current drawn, restrictions on moving parts etc. Keeping these in mind "Insert Conference Plan Table here" 
Simulation 
I did modal analysis for some reason:

![alt text][rod-modal-analysis]

CAD Design

![alt text][board]

Electronics - PCB Design (not the actual design right? Maybe a simplified block diagram?)
Validation
1st prototype implemented
Modular software architecture
Testing
Vibration Tests
Thermovac
??? Test
Data
Understanding the material stress; transition effects; durability?
Basic plots (offline/ground data)
Results
Awaiting launch
Future Improvements
Ground Station
Design optimization
Other smart materials to look into - NiMnGa

[rod-modal-analysis]: _static/rod_modal_analysis_1.png "1st Natural Freq of rod"
[board]: _static/board_1.png "1st Natural Freq of rod"
