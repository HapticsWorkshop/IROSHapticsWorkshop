---
title: "Hybrid Modular Robotic Touch Rendering"
poster_id: "A03"
section: "A"
summary_image: /assets/images/posters/a03-an.jpg
excerpt: "Haptic interfaces for augmented and virtual reality can reproduce individual cues such as force, texture, shape, and compliance, yet these properties are often rendered using…"
authors:
  - name: "Nan An"
    family: "An"
    affiliations: ["Carnegie Mellon University"]
  - name: "Carmel Majidi"
    family: "Majidi"
    affiliations: ["Carnegie Mellon University"]
---

Haptic interfaces for augmented and virtual reality can reproduce individual cues such as force, texture, shape, and compliance, yet these properties are often rendered using dedicated mechanisms designed for specific interaction geometries. This limits the reuse of a single physical interface across diverse virtual objects and scenarios. We propose a modular robotic haptic rendering framework in which a six-degree-of-freedom robotic arm repositions interchangeable physical modules to reproduce local properties of virtual surfaces. The approach separates global spatial rendering, handled through robot motion, from local haptic characteristics provided by the physical module.

The current prototype focuses on geometric rendering using geometrically identical modules of varying materials containing point, edge, planar, and curved features. Virtual contact positions and local geometric features are mapped onto corresponding physical features, while a real-time trajectory-generation and control pipeline maintains the required contact position and orientation. The system first establishes physical contact while maintaining the required contact orientation and subsequently enables continuous surface-constrained following as the virtual contact moves. Rather than physically reproducing an entire virtual object, reusable local geometric primitives can therefore be repositioned and reoriented to represent a larger set of virtual surface features. Initial experiments demonstrate continuous contact tracking over basic geometries while preserving the intended contact position and orientation.

With this formulation, we also treat module orientation and robot transitions between geometric features as an optimization problem, aiming to reduce transition latency while maintaining reliable contact and feature correspondence. The same modular architecture is intended to support future integration of material variation, controllable compliance, active shape modulation, and vibrotactile texture within a common robotic haptic rendering framework.
