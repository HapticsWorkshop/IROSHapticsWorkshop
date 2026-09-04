---
title: "Tactile-Enabled Contact Insertion for Automated Wire-Harness Assembly"
poster_id: "B01"
section: "B"
summary_image: /assets/images/posters/b01-lakkavalli-giridhar.jpg
excerpt: "Wire-harness assembly remains largely manual in vehicle production, and one step of it is inserting a crimped contact into a connector cavity. The gripper must stop at the crimp…"
authors:
  - name: "Namya Lakkavalli Giridhar"
    family: "Lakkavalli Giridhar"
    affiliations: ["Carnegie Mellon University"]
  - name: "Atharv Mendhe"
    family: "Mendhe"
    affiliations: ["Mowito"]
  - name: "Gautam Manu"
    family: "Manu"
    affiliations: ["Mowito"]
  - name: "Safar Vellanchola"
    family: "Vellanchola"
    affiliations: ["Mowito"]
---

Wire-harness assembly remains largely manual in vehicle production, and one step of it is inserting a crimped contact into a connector cavity. The gripper must stop at the crimp, but once the wire is held between the fingers the contact is hidden from the camera. Robotic manipulation still leans predominantly on vision, and this is a case where vision cannot close the loop.

We present a tactile-enabled system for this step, built around an off-the-shelf industrial two-finger gripper with one finger replaced by a DIGIT visuo-tactile sensor. A CNN-based classifier distinguishes bare wire from the crimped terminal, and tactile feedback stops the gripper at the crimp edge, resolving the grasp point. Classical control then performs the insertion. A YOLO26s-obb detector locates the wire end and type, an AprilTag planar correction handles the coaxial contact, and six-degree-of-freedom pose correction under image-based visual servoing handles the rectangular single-wire contact.

The system was part of Mowito’s entry to the 2026 Robotik Challenge, an externally judged benchmark with published part numbers, where it received the award for Technological Innovation. One sensor and one learned classifier served both wire types despite their different contact shapes. The tactile stage ran in all 60 trial insertions, and no insertion failure was attributed to the tactile decision. The coaxial line succeeded in 29 of 30 insertions under a planar correction, while the single wire, requiring the full six-degree-of-freedom correction, succeeded in 15 of 30. Tactile sensing closes the loop where vision cannot, on real hardware. The tactile decision is only as good as the grasp itself, and the gripper required position-control retuning before it could stop repeatably at the crimp. This is a hardware-software co-design problem. Speed and insertion accuracy can still be improved, and exploring end-to-end learning-based methods is future work.
