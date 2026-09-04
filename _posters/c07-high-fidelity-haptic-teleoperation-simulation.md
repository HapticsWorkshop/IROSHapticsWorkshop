---
title: "High-Fidelity Haptic Teleoperation in Robotics Simulation via Multi-Rate Reduced Interface Models"
poster_id: "C07"
section: "C"
summary_image: /assets/images/posters/c07-sirois.jpg
excerpt: "Collecting high-quality human demonstrations for contact-rich manipulation in simulation remains difficult. Current teleoperation methods rely on visual feedback which make it…"
authors:
  - name: "Charles Sirois"
    family: "Sirois"
    affiliations: ["McGill University"]
  - name: "Joe Hewlett"
    family: "Hewlett"
    affiliations: ["CM Labs"]
  - name: "Jozsef Kovecses"
    family: "Kovecses"
    affiliations: ["McGill University"]
---

Collecting high-quality human demonstrations for contact-rich manipulation in simulation remains difficult. Current teleoperation methods rely on visual feedback which make it hard for the operator to perform complex manipulation task. While haptic feedback is a promising solution, a critical frequency mismatch exists: realistic force feedback requires kilohertz-rate rendering to ensure stability and transparency, whereas physics simulators (e.g., Isaac Sim) are computationally constrained to much lower rates, typically around 50Hz. Conventional multi-rate approaches, such as interpolation or extrapolation, lack physical consistency, often leading to instability or perceived artifacts during stiff contact events.

In this work, we propose a novel multi-rate framework that bridges this frequency gap using a Reduced Interface Model (RIM). While prior RIM formulations effectively couple haptic devices to passive virtual environments, they fail when interacting with robots under active control. We extend the RIM formulation by using it as an Inertial Proxy that the robot tracks, rather than a predictor of its behaviour. By integrating a unilateral contact solver within this reduced representation, we enable the rendering of nonsmooth dynamics---switching between free motion and hard contact---at the high haptic rate.

We validate the proposed framework by teleoperating a Franka Research 3 arm in Isaac Sim using a Haply Inverse 3 haptic device. We demonstrate the system's efficacy in a constrained manipulation task involving continuous sliding contact. Results show that our method significantly improves high-frequency force transparency and user perception compared to standard sampling baselines, while ensuring coupled stability even during stiff, unilateral contact events. This approach provides a scalable pathway for generating high-fidelity tactile data for Sim2Real and imitation learning applications.
