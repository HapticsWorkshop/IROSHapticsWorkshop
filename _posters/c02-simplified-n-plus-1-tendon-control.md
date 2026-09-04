---
title: "Simplified N+1 Tendon Control with Rolling-Contact Joints"
poster_id: "C02"
section: "C"
summary_image: /assets/images/posters/c02-dills.jpg
excerpt: "Kinesthetic haptic feedback, bilateral teleoperation, and highly dexterous robotic manipulation depend on force control. In force control, remotely locating actuators away from a…"
authors:
  - name: "Patrick Dills"
    family: "Dills"
    affiliations: ["Northwestern University"]
  - name: "J. Edward Colgate"
    family: "Colgate"
    affiliations: ["Northwestern University"]
---

Kinesthetic haptic feedback, bilateral teleoperation, and highly dexterous robotic manipulation depend on force control. In force control, remotely locating actuators away from a manipulator’s driving point and joints is advantageous in terms of the robot’s form factor and inertia. A popular method to accomplish remote actuation is “N+1” control where an N-degree of freedom manipulator is controlled by N+1 antagonistically controlled tendons. While N+1 control reduces the number of tendons to fully control a manipulator, the approach results in a tendon tension null space that must be resolved at each control step to ensure that all tendons are taut. This complicates real-time control. We present an N+1 tendon tension control method that provides much of the design flexibility of more general N+1 systems while avoiding the control complexity. We accomplish simplified control using rolling contact joints. Rolling contact joints enable selectively routing tendons through the center of a joint such that they result in zero moment about the joint. We show that doing so leads to a family of N+1 controllers in which transforming joint torques to tendon tensions can be achieved computationally cheaply and in closed form, while also minimizing the sum of feasible tendon tensions. Finally, we present a prototype N+1 rolling-contact robot finger designed around these properties and discuss its planned force-control implementation.
