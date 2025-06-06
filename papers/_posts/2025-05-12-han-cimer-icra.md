---
layout: paper
title: CIMER&#58; Combining Imitation and Emulation to Learn Prehensile Dexterity from State-only Observations
image: /papers/images/han-cimer-2.png
authors: Yunhai Han, Zhenyang Chen, Kyle A Williams, Harish Ravichandar
year: 2025
ref: Han et al., ICRA 2025.
journal: "IEEE International Conference on Robotics and Automation (ICRA)"
arxiv: 2404.05582
github: GT-STAR-Lab/CIMER
supplement: https://sites.google.com/view/cimer-2024/

---

## Abstract

When human acquire physical skills (e.g., tennis) from experts, we tend to first learn from merely observing the expert. But this is often insufficient. We then engage in practice, where we try to emulate the expert and ensure that our actions produce similar effects on our environment. Inspired by this observation, we introduce Combining IMitation and Emulation for Motion Refinement (CIMER) -- a two-stage framework to learn dexterous prehensile manipulation skills from state-only observations.  CIMER's first stage involves imitation: simultaneously encode the complex interdependent motions of the robot hand and the object in a structured dynamical system. This results in a reactive motion generation policy that provides a reasonable motion prior, but lacks the ability to reason about contact effects due to the lack of action labels. The second stage involves emulation: learn a motion refinement policy via reinforcement that adjusts the robot hand's motion prior such that the desired object motion is reenacted. CIMER is both task-agnostic (no task-specific reward design or shaping) and intervention-free (no additional teleoperated or labeled demonstrations). Detailed experiments with prehensile dexterity reveal that i) imitation alone is insufficient, but adding emulation drastically improves performance, ii) CIMER outperforms existing methods in terms of sample efficiency and the ability to generate realistic and stable motions, iii) CIMER can either zero-shot generalize or learn to adapt to novel objects from the YCB dataset, even outperforming expert policies trained with action labels in most cases. Source code and videos are available at https://sites.google.com/view/kodex-corl.