---
title: "Blind Whole-Body Haptic Dexterity Without Tactile Sensors"
poster_id: "C04"
section: "C"
summary_image: /assets/images/posters/c04-bhatt.jpg
excerpt: "Robotic haptic perception is usually framed as a hardware problem: add tactile or force/torque sensors to make contact observable. Across Blind Dexterity and The Blind…"
authors:
  - name: "Aditya Bhatt"
    family: "Bhatt"
    affiliations: ["DFKI GmbH", "TU Darmstadt"]
  - name: "Ansh Prakash"
    family: "Prakash"
    affiliations: ["DFKI GmbH", "TU Darmstadt"]
  - name: "Oleg Kaidanov"
    family: "Kaidanov"
    affiliations: ["TU Darmstadt"]
  - name: "Joao Carvalho"
    family: "Carvalho"
    affiliations: ["DFKI GmbH", "TU Darmstadt"]
  - name: "Puze Liu"
    family: "Liu"
    affiliations: ["Tongji University", "Shanghai Research Institute for Autonomous Intelligent Systems"]
  - name: "Jan Peters"
    family: "Peters"
    affiliations: ["DFKI GmbH", "TU Darmstadt"]
---

Robotic haptic perception is usually framed as a hardware problem: add tactile or force/torque sensors to make contact observable. Across Blind Dexterity and The Blind Skateboarder, we test a complementary possibility: a standard humanoid without dedicated contact sensors may already possess a whole-body haptic channel in its control loop.

To probe the limits of manipulation under sensory deprivation, we train blind manipulation policies by withholding object state. The resulting policies do not merely experience contact—they actively seek and shape it. A foot sweeps for a football or skateboard; contact with the board’s nose, tail, and edge resolves geometric ambiguities; plastic hands tap a table and suitcase before seeking out a recessed handle. On a skateboard, the robot converges to maneuver-specific footholds and executes, to our knowledge, the first repertoire of skateboard tricks by a robot, including ollies, pop shove-its, and kickflips.

These behaviors reveal a control principle: purposeful motion turns ordinary onboard feedback into haptic evidence. Contact-induced deflections and tracking errors are not merely disturbances to reject; they are measurements the policy can create and interpret. Histories of joint encoders, IMU readings, and recent actions reveal these responses. We train auxiliary estimators to recover object pose from these histories. Their prediction errors drop sharply after informative contact, showing that task-relevant object state (e.g. pose) can be inferred without visual tracking.

We therefore argue that whole-body haptic perception is partly a control problem, not only a sensor-design problem. Existing robots can acquire a coarse, immediately available sense of touch by learning where, when, and how to make contact. Tactile sensors remain valuable for resolving ambiguities and contact geometry, but they should augment a haptic channel already present in the whole-body control loop rather than be treated as its sole source.
