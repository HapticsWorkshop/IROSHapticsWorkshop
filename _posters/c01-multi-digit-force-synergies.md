---
title: "Multi-digit Force Synergies for Haptic Interface Design"
poster_id: "C01"
section: "C"
summary_image: /assets/images/posters/c01-zuo.jpg
excerpt: "In-hand manipulation is essential for achieving high-performance control in teleoperated robotics and enabling immersive, embodied interactions in virtual environments. It…"
authors:
  - name: "Kaiwen Zuo"
    family: "Zuo"
    affiliations: ["Case Western Reserve University"]
  - name: "Tianshu Yang"
    family: "Yang"
    affiliations: ["Case Western Reserve University"]
  - name: "Zonghe Chua"
    family: "Chua"
    affiliations: ["Case Western Reserve University"]
---

In-hand manipulation is essential for achieving high-performance control in teleoperated robotics and enabling immersive, embodied interactions in virtual environments. It involves contact-rich, single-handed movements involving multiple digits (e.g., squeezing, rocking, flipping, and translating an object) to accomplish dexterous tasks. In robotics, advances have been made in the design of highly dexterous hands for in-hand manipulations. However, haptic interfaces for teleoperating these hands are still mostly designed for static grasping. Designing for in-hand manipulation requires negotiating difficult tradeoffs in functionality and wearability, creating a barrier to further development. Furthermore, compared with static grasping, the critical haptic dimensions underlying successful in-hand manipulation remain poorly understood, limiting the principles available to inform haptic interface design.

To investigate these challenges, we developed a free-hand manipulation setup in which users manipulate customized cylindrical objects of varying diameters. Each object integrates three load cells to measure the forces applied by the thumb, index, and middle finger. We define a human-perceived force coordinate frame for each finger, in which the measured force is decomposed into traction (X), lateral (Y), and normal (Z) components. Unlike conventional contact coordinate frames defined with respect to the normal of the local contact surface, the proposed coordinate frame is defined relative to the finger and therefore moves with the finger during manipulation. The pose of each finger is tracked using electromagnetic trackers mounted on the fingertip, and the measured load-cell forces are transformed into the corresponding human-perceived force coordinate frame based on the tracked finger pose.

Preliminary measurements demonstrate the functionality of the proposed setup and suggest distinct multi-digit force correlations across different manipulation motions. Future work will involve a systematic user study to further investigate multi-digit force patterns across in-hand manipulation tasks.
