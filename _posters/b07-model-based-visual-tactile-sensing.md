---
title: "A Model-based Visual Tactile Sensing and Perception System for Compliant Robotic Grippers"
poster_id: "B07"
section: "B"
summary_image: /assets/images/posters/b07-zuo.jpg
excerpt: "Tactile sensing is essential for robotic manipulation, yet integrating traditional force/torque (F/T) sensors into compliant grippers introduces trade-offs in sensing performance…"
authors:
  - name: "Kaiwen Zuo"
    family: "Zuo"
    affiliations: ["Case Western Reserve University"]
  - name: "Shuyuan Yang"
    family: "Yang"
    affiliations: ["Case Western Reserve University"]
  - name: "Zonghe Chua"
    family: "Chua"
    affiliations: ["Case Western Reserve University"]
---

Tactile sensing is essential for robotic manipulation, yet integrating traditional force/torque (F/T) sensors into compliant grippers introduces trade-offs in sensing performance, mechanical robustness, cost, and structural compliance. Traditional strain-gauge sensors can be vulnerable to impact, while embedded sensors may interfere with the natural deformation of soft grippers. To address these challenges, we present a model-based visual tactile sensing framework that uses a wrist-mounted RGB-D camera to infer contact and force information from the deformation of fin-ray-shaped compliant grippers. Structural key points extracted from the RGB-D camera are incorporated into real-time inverse finite element analysis (iFEA) to estimate grasp forces without embedding sensing elements into the gripper. To enable robust tactile perception during continuous manipulation, where grasp poses and contact locations may change, we introduce an iterative contact localization algorithm that combines the deformed gripper geometry with reconstructed object geometry to dynamically update contact estimates. An image-based mesh reconstruction pipeline further enables the framework to generalize to previously unseen objects.

The proposed system was evaluated through both static and on-robot grasping experiments across different object geometries, contact locations, and force levels. It achieved an average RMSE of 0.23 N and a normalized root mean square deviation of 2.11% during loading and 0.48 N and 4.34% over the entire grasping process, while demonstrating improved generalization compared with an end-to-end learning baseline. Finally, force-controlled grasping and lifting of a fragile potato chip demonstrate the potential of the proposed framework for tactile-aware manipulation of delicate objects.
