---
title: "Large-Area Tactile Sensing via Contact-Induced Modulation of Ultrasonic Waves"
poster_id: "B04"
section: "B"
summary_image: /assets/images/posters/b04-reardon.jpg
excerpt: "Tactile sensing on robot hands is typically concentrated at the fingertips, yet contact during grasping and in-hand manipulation frequently occurs across the palm, proximal…"
authors:
  - name: "Gregory Reardon"
    family: "Reardon"
    affiliations: ["Northwestern University"]
  - name: "Mark Beliaev"
    family: "Beliaev"
    affiliations: []
  - name: "Kaival Shah"
    family: "Shah"
    affiliations: ["Northwestern University"]
  - name: "Rohan Kota"
    family: "Kota"
    affiliations: ["Northwestern University"]
  - name: "Michael Peshkin"
    family: "Peshkin"
    affiliations: ["Northwestern University"]
  - name: "J. Edward Colgate"
    family: "Colgate"
    affiliations: ["Northwestern University"]
---

Tactile sensing on robot hands is typically concentrated at the fingertips, yet contact during grasping and in-hand manipulation frequently occurs across the palm, proximal regions of the fingers, and sides of the fingers. Broader interactions with the environment may additionally involve the back of the hand or the forearm. Capturing these interactions therefore calls for tactile sensing across increasingly large portions of the robot hand and arm. Achieving this coverage with existing tactile sensing technologies remains challenging. In array-based approaches, the number of sensing elements and associated readout complexity can grow substantially with sensing area; optical approaches require imaging hardware that can be difficult to accommodate in a thin, compact package as sensing coverage extends beyond localized regions.

Here, we introduce an ultrasound-based approach to large-area tactile sensing that requires only a small number of piezoelectric transducers embedded in a thin, soft elastomer. Our method employs a dual-plate architecture in which contact with the environment brings two soft plates together, substantially altering the propagation of actively generated 1 MHz ultrasonic waves through the system. We demonstrate that these contact-induced waveform modulations enable sub-millimeter contact localization across a 25 cm2 sensing surface and normal-force estimation over a 0–10 N range, with median errors of ~600 μm and ~175 mN, respectively. We achieve this performance using waveforms recorded by as few as two piezoelectric receivers and a two-stage prediction framework in which a waveform encoder is trained with a Rank-N-Contrast loss and then frozen for downstream regression. Ongoing work extends this architecture to a forearm-scale sensor to evaluate how sensing performance and hardware requirements scale with increasing area. The present results suggest that ultrasound-based tactile sensing may provide a low-complexity, easy-to-fabricate route to large-area tactile coverage that supports more dexterous robotic manipulation.
