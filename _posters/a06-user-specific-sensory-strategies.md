---
title: "Learning User-Specific Sensory Strategies from Haptic Interaction"
poster_id: "A06"
section: "A"
summary_image: /assets/images/posters/a06-chase.jpg
excerpt: "Haptic interfaces for teleoperation and human-robot interaction often assume that users interpret feedback similarly, yet perception depends on how haptic cues are integrated with…"
authors:
  - name: "Elyse Chase"
    family: "Chase"
    affiliations: ["University of Houston"]
  - name: "Marcia O'Malley"
    family: "O'Malley"
    affiliations: ["Rice University"]
---

Haptic interfaces for teleoperation and human-robot interaction often assume that users interpret feedback similarly, yet perception depends on how haptic cues are integrated with vision and proprioception, and on whether the user actively controls the interaction. We present a hierarchical Bayesian sensory-evidence model that infers user-specific weights on haptic force, visual motion, and proprioceptive movement from trial-level interaction data and perceptual decisions. We apply the model to two prior virtual reality stiffness studies that used wrist-worn squeeze feedback with applied visual hand remapping, leading to mismatched visual hand motion and proprioceptive movement cues. During active touch, the inferred weights revealed force-dominant, mixed, and vision/proprioception-dominant sensory profiles. These model-derived profiles aligned with independently observed haptic- and visual-prior behavioral strategies that were not used during model fitting. In a second dataset comparing active exploration with passive replay of the same sensory feedback, condition-specific modeling showed that removing active control altered the relative composition of sensory evidence in user- and subgroup-dependent ways, with the clearest qualitative change being reduced relative proprioceptive weighting during passive replay. Population-level signed shifts remained uncertain, underscoring the importance of modeling individual users rather than relying solely on group averages. These results show that haptic interaction logs can reveal how a specific user interprets multisensory feedback, providing a computational foundation for adaptive haptic interfaces that personalize feedback during teleoperation, shared control, and other human-in-the-loop robotic interactions.
