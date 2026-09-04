---
title: "Bringing Human Touch to Robot Hands: A Force-Transparent Teleoperation System for Bilateral Control"
poster_id: "C08"
section: "C"
summary_image: /assets/images/posters/c08-sterling-angus.jpg
excerpt: "Dexterous teleoperation leverages a human operator’s natural dexterity to control contact-rich robotic interactions and collect demonstration data for robot learning. Operator…"
authors:
  - name: "Oliver Sterling-Angus"
    family: "Sterling-Angus"
    affiliations: ["Northwestern University"]
  - name: "Luke Batteas"
    family: "Batteas"
    affiliations: ["Northwestern University"]
  - name: "Kevin Lynch"
    family: "Lynch"
    affiliations: ["Northwestern University"]
  - name: "J. Edward Colgate"
    family: "Colgate"
    affiliations: ["Northwestern University"]
---

Dexterous teleoperation leverages a human operator’s natural dexterity to control contact-rich robotic interactions and collect demonstration data for robot learning. Operator performance, however, depends on the quality of haptic feedback rendered to the user. Most dexterous teleoperation systems provide only one degree of force feedback per finger, causing forces orthogonal to the display direction to be lost. This incomplete feedback can lead operators to misinterpret contact and select inappropriate actions. Providing multidirectional fingertip feedback requires high-DOF haptic interfaces, but accurate rendering also requires the motions and forces of the interface and robot hand to remain synchronized. Bilateral control can tightly couple the two devices, but the force transparency, or how faithfully forces are transmitted between them, depends on their mechanical properties. Although haptic interfaces are typically designed for low mechanical impedance, robot hands often use high transmission ratios and exhibit substantial friction and reflected inertia. These properties reduce backdrivability and distort the forces transmitted to the operator. We hypothesize that co-designing both devices for multidirectional feedback and low mechanical impedance will improve teleoperation performance and produce higher-quality demonstrations for robot learning.

We present a dexterous teleoperation system comprising a three-fingered, 3DOF-per-finger exoskeleton haptic interface and matching robotic hand. Both devices use stiff tendon transmissions to remotize the actuators, reducing moving mass while preserving transmission stiffness. Low mechanical impedance is achieved using small transmission ratios to minimize reflected actuator inertia and ball-bearing-guided tendon paths to reduce friction. This design ensures each device is backdrivable with improved force transparency across the teleoperation loop. The haptic interface can deliver ~15N of force feedback via linkages that route over the back of the hand and allow for unimpeded in-hand manipulation. This system enables investigation of how high-quality fingertip feedback affects teleoperation performance and whether those effects propagate through demonstration data to learned robot policies.
