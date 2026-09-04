---
title: "Learning Bimanual Dexterous Jar Opening with Finger Gaiting"
poster_id: "C06"
section: "C"
summary_image: /assets/images/posters/c06-xu.jpg
excerpt: "This paper presents a bimanual dexterous system that learns contact-rich jar opening through reinforcement learning without human demonstrations. Starting from pre-grasp…"
authors:
  - name: "Mo Xu"
    family: "Xu"
    affiliations: ["University of Wisconsin"]
  - name: "Yunfu Deng"
    family: "Deng"
    affiliations: ["University of Wisconsin"]
  - name: "Jianuo Wang"
    family: "Wang"
    affiliations: ["University of Michigan"]
  - name: "Josiah Hanna"
    family: "Hanna"
    affiliations: ["University of Wisconsin"]
  - name: "Bilge Mutlu"
    family: "Mutlu"
    affiliations: ["University of Wisconsin"]
---

This paper presents a bimanual dexterous system that learns contact-rich jar opening through reinforcement learning without human demonstrations. Starting from pre-grasp configurations, a single policy coordinates both robot arms and multi-fingered hands to acquire separate grasps on the jar body and lid, stabilize the jar, and sustain lid twisting. A fixed finger contact configuration provides only a limited range of lid rotation as the twisting fingers approach their kinematic limits. Continuing to twist beyond this range involves changing the finger contacts while maintaining control of the lid and keeping the jar stable.

To facilitate learning, we introduce a geometric enclosure representation that describes the spatial relation between the fingers and the object and guides the fingers to form stable grasps around the jar body and lid. Training follows a three-stage curriculum for foundational skill acquisition, finger skill exploration, and sim-to-real adaptation. The learned policy executes asynchronous finger gaiting for sustained twisting. As a twisting finger approaches its kinematic limit, it releases the lid, repositions, and reestablishes contact, while the other engaged fingers maintain contact and continue rotating the lid.

The learned policy transfers to the physical bimanual system, where it performs sustained twisting and achieves complete lid disengagement on both the 3D-printed jar and diverse household containers. The results demonstrate bimanual jar opening from grasp acquisition through sustained twisting, with finger gaiting emerging through reinforcement learning and transferring to the real world.
