# Spyn (2021)
## Problem Statement
People with disabilities face many challenges and barriers in accessing transportation options, especially in urban areas. They often have to rely on public transit, paratransit, or personal assistance, which can be costly, unreliable, or inconvenient. Moreover, they may encounter physical, social, or attitudinal obstacles that limit their mobility and independence. Therefore, there is a need for a transportation system that can accommodate the diverse needs and preferences of people with disabilities, and provide them with safe, comfortable, and efficient mobility solutions.

## Proposed Solution
SPYN is an innovative transportation system that provides accessible and convenient mobility for people with disabilities. SPYN vehicles are fully autonomous, requiring no human driver or intervention. Users can request a SPYN vehicle through a mobile app, which verifies their eligibility and matches them with the nearest available vehicle. SPYN vehicles are designed to operate in urban areas, with plans to expand to smaller cities in the future. SPYN vehicles ensure the safety and comfort of their passengers by securing their wheelchairs, providing an accessible user interface, and offering emergency buttons within reach. SPYN aims to empower people with disabilities to travel independently and efficiently. </br>

This project aimed to create the running program that would automate the functions of the vehicle which are to: </br>
1. Navigate a maze efficiently to get from starting position to the client
   - Create functions for the vehicle to sensor stopping points indicated on the ground by different colored tapes
   - Use distance sensor to navigate maze openings
3. Pick up the client in wheelchair
   - Use claw mechanism and prototype the controls to pick up client securely
5. Safely carry and navigate the client to their final destination

## Obstacles and Overcoming
1. Turning Radius
   - Undergo multiple test runs with the vehicle while tinkering with motor speeds
   - Routinely checking and charging ehicle batteries to ensure consistent motor speeds
3. Sensor Errors
   - Hardware checks before every test run
   - Mapping out the radius of distance sensor to understand variable sensitivity and documenting each variable shift for future referencing
   - Color sensor recalibrations for RGB values as well as light sensitivities (night/day)
5. Claw Mechanism for Picking up Fragile Client Prototype
   - Built multiple prototypes for the safetest and most secure pick up method considering the following:
       - Clients are waiting at pick up spot facing the vehicle
       - Size of the wheelchair and positioning of client in the wheelchair
       - Vehicle's only indicator for drop-off location is via ground sensor
       - Vehicle needs to ensure that the wheelchair remains secure throughout return path route. 

## Presentation Video: https://www.youtube.com/watch?v=gPBQM6YwkF8

## State Diagram
![image](https://github.com/KayeJD/Spyn/assets/139111295/f2cb7467-b28b-4cd4-b8aa-c86d2b5edf69)

## Vehicle Design
### Brainstorming Design
![image](https://github.com/KayeJD/Spyn/assets/139111295/d2f96d1d-cf00-49fe-8f63-556a4b37cff9)


### Final Prototype
![image](https://github.com/KayeJD/Spyn/assets/139111295/f63b2fcf-4ecb-4869-b424-ed0e7aa44ecc)
![image](https://github.com/KayeJD/Spyn/assets/139111295/8e5e4688-6b2d-4594-b2ed-2f5442bfdc5a)
![image](https://github.com/KayeJD/Spyn/assets/139111295/b8bb4987-50f5-4ca0-8f4d-7b2a3bfd5af0)
