---
title: "ReFineGrasp: Visual-Tactile Property Refinement for Adaptive Grasping of Delicate Objects"
poster_id: "B06"
section: "B"
summary_image: /assets/images/posters/b06-yoshida.jpg
excerpt: "Robotic manipulation in unstructured household environments requires robots to handle diverse and unfamiliar objects without causing damage. This remains challenging because…"
authors:
  - name: "Kaoru Yoshida"
    family: "Yoshida"
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

Robotic manipulation in unstructured household environments requires robots to handle diverse and unfamiliar objects without causing damage. This remains challenging because visual appearance alone provides limited information about physical properties such as mass, material, compliance, and friction. Although vision and touch offer complementary information, many existing methods treat pre-contact visual estimation and post-contact interaction sensing separately. This paper introduces ReFineGrasp, a visual-tactile framework for refining object property estimates through physical interaction. First, a vision-language model (VLM) predicts an initial property belief from a segmented pre-contact RGB image. The robot then performs a selected exploratory action, such as grasp-and-lift, squeezing from different orientations, or controlled sliding, while recording synchronized fingertip normal and shear signals, hand joint angles, and actuator feedback. The VLM subsequently uses these multimodal interaction observations together with the visual prior to update the estimated physical properties and their uncertainty. We first evaluate which properties are most effectively refined by each action by comparing the visual prior and interaction-informed estimates against manually measured ground truth. We use these results to identify the most informative action for each physical property, with the goal of selecting actions and adapting the final grasp accordingly. Experiments use a robotic manipulator equipped with an INSPIRE dexterous hand and evaluate estimation accuracy, repeatability, grasp success, object deformation, and applied force on various household objects. By integrating visual priors with action-conditioned physical evidence, ReFineGrasp aims to enable safer and more adaptive manipulation of unfamiliar objects in unstructured environments.
