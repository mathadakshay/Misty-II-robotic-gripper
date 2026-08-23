# Misty II Robotic Gripper Development

> Two-finger robotic gripper for Planning Poker card manipulation on Misty II.

**Status:** Ongoing  
**Institution:** BHT Berlin  
**Project Type:** Studies Internship / Robotics Hardware Development  
**Tools:** SolidWorks, 3D Printing, Mechanical Prototyping

## Project Overview

This ongoing project focuses on the design and prototyping of a two-finger robotic gripper for Misty II, developed as part of my studies internship at BHT Berlin.

The gripper is designed for Planning Poker card manipulation and uses a geared mechanical transmission to control finger opening and closing.

## Project Objectives

- Design a compact two-finger gripper in SolidWorks.
- Develop a mechanical transmission for controlled finger movement.
- Convert rotary actuator motion into linear rack movement (Scotch Yoke mechanism)
- Prototype and evaluate the mechanism through 3D printing.
- Prepare the gripper for future Dynamixel XL330 and software integration.

## Mechanical Design

The gripper was designed in SolidWorks with a spur gear and rectangular rack mechanism for finger actuation.

The current mechanical transmission follows:

XL330 Motor → Crank → Scotch yoke → Rectangular Rack → Spur Gears → Fingers

![CAD Assembly](images/cad-assembly.png)

## Rotary-to-Linear Motion

A Scotch yoke mechanism is used to convert rotary motion into linear forward and backward movement of the rectangular rack.

The crank was intentionally designed with an approximately 50 mm diameter to provide a larger rack travel during one complete rotation.

![Scotch Yoke Mechanism](images/scotch-yoke-mechanism.png)

## Gear Mechanism

The rectangular rack engages with the spur gear transmission to transfer the rack movement to the gripper fingers.

The gear and rack geometry is currently being optimized to achieve smoother and more reliable mechanical movement.

![Gear Mechanism](images/gear-mechanism.png)

## 3D-Printed Prototype

The first physical prototype was produced using PLA to validate the SolidWorks design and mechanical transmission.

Since the original Dynamixel XL330 is currently not available for physical testing, a 3D-printed motor replacement was used as a mechanical substitute.

![3D Printed Prototype](images/printed-prototype.jpg)

## Current Finger Movement

The current mechanism demonstrates:

- Clockwise rotation → fingers close
- Counterclockwise rotation → fingers open

A SolidWorks motion demonstration is included below.

## Material Iteration

PLA was used for the first prototype to validate the mechanical geometry.

The gear interface is currently being optimized for smoother and lower-friction movement. The next prototype will evaluate PETG or another suitable material for improved mechanical performance.

## Current Status

- First SolidWorks gripper design completed.
- First 3D-printed prototype produced.
- Rotary-to-linear mechanism prototyped.
- Spur and rack gear transmission implemented.
- Finger opening and closing demonstrated in CAD.
- Mechanical design and material selection currently under iteration.

## Next Steps

1. Optimize the gear and rack interface for smoother movement.
2. Evaluate PETG and other suitable materials.
3. Replace the printed motor model with the Dynamixel XL330.
4. Implement Python-based gripper control.
5. Integrate the gripper actuator with the Misty II platform.

