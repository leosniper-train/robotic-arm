# Robotic Arm

## Quick orientation

This is the compact, colorful member of the collection: a blue and red articulated arm mounted on a dark pedestal and finished with a small two-finger gripper. It is a useful assembly for studying a robot's posture, reach, and visual separation of its major mechanisms.

The arm's job is straightforward: move the gripper through space, then present the fingers to an object for a grasp or transfer. The model is therefore best understood as a mechanical layout and pose reference, not as a complete electrically controlled robot.

## Three ways to read the model

### The complete mechanism

![Raised compact arm](<image (8).png>)

The raised pose shows the full path from the mounting plate to the open gripper. The blue structural links, red joint pieces, and black housings make the assembly's layers easy to distinguish.

### The folded posture

![Folded compact arm](<image.png>)

With the arm bent upward, the elbow and wrist become the main subjects. This pose is useful when thinking about how the robot stores its links or approaches an object from above.

### The construction view

![SolidWorks construction view](<Screenshot 2026-09-11 235618.png>)

The CAD view uses transparency and selection to expose the pedestal and mounting arrangement beneath the links. It is the best image for checking how the visible outer pieces relate to the assembly structure.

## Contents

There is one top-level file, `Assem.SLDASM`. Open it in SolidWorks to explore the assembly and its movable relationships.

## Current scope

No payload, speed, actuator, sensor, controller, or production dimensions are specified here. Check joint travel, interference, fastening, gripper force, and structural loads before using the concept as hardware.
