---
title: "Multi-Modal Demonstrations for Dexterous Manipulation"
poster_id: "C05"
section: "C"
summary_image: /assets/images/posters/c05-tamura.jpg
excerpt: "Collecting demonstrations for long-horizon, contact-rich manipulation remains a major bottleneck in robot learning. Teleoperation scales to long-horizon tasks but is imprecise for…"
authors:
  - name: "Ryosei Tamura"
    family: "Tamura"
    affiliations: ["Keio University"]
  - name: "Uksang Yoo"
    family: "Yoo"
    affiliations: ["University of California, Berkeley"]
  - name: "Yuemin Mao"
    family: "Mao"
    affiliations: ["Carnegie Mellon University"]
  - name: "Jeffrey Ichnowski"
    family: "Ichnowski"
    affiliations: ["Carnegie Mellon University"]
---

Collecting demonstrations for long-horizon, contact-rich manipulation remains a major bottleneck in robot learning. Teleoperation scales to long-horizon tasks but is imprecise for fine, contact-rich interaction, whereas kinesthetic teaching excels at contact-rich manipulation but is physically exhausting and, critically, records the demonstrator's hands in every frame. This paper investigates how teleoperation and kinesthetic teaching can be combined for training policies for dexterous manipulation. We propose a demonstration framework that uses teleoperation data for broad task execution and kinesthetic teaching for difficult fine-control phases. We first train a diffusion policy on teleoperated demonstrations, then refine it through real-time kinesthetic alignment. Because the human hand appears during correction but not at deployment, we supervise the visual encoder with object masks so it attends to the manipulated object rather than the demonstrator's hand. We were able to visualize the visual encoder that attends more to the manipulated object. This work suggests that combining heterogeneous demonstration types allows a single policy to handle both long-horizon execution and fine-grained contact-rich phases of dexterous manipulation.
