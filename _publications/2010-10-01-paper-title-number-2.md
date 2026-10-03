---
title: "Decomposed Affordance Selection and Latent Generation for Physically Plausible Human-Scene Interaction"
collection: publications
category: manuscripts
permalink: /publication/2026-03-01-deseg-wacv
excerpt: 'We present DeSeG, a two-stage framework that decomposes affordance selection from latent-conditioned motion generation for language-conditioned human-scene interaction.'
date: 2026-03-01
status: under_review
venue: 'Under Review at WACV'
paperurl: 'https://arxiv.org/abs/2607.05787'
# citation: 'Jiakun Li*, Zhe Li*, <b>Wenqiang Wu*</b>, Zheng Chang, Mingqi Gao, Jinyu Yang, Feng Zheng. (&ast;Equal contribution). &quot;Decomposed Affordance Selection and Latent Generation for Physically Plausible Human-Scene Interaction.&quot; <i>Under Review at WACV 2027</i>.'
---

<!-- The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font. -->
---

### Abstract
We propose DeSeG, a hierarchical framework that decouples high-level semantic interaction planning from low-level geometric motion execution for physically plausible 3D Human-Scene Interaction (HSI) synthesis. By combining a latent multimodal planner with a physics-regularized diffusion executor, DeSeG achieves precise semantic controllability while significantly mitigating scene collisions without requiring computational-heavy test-time optimization

### Key Contributions
* **Decoupled Hierarchical Architecture:** Introduced a novel two-stage framework that explicitly decouples high-level semantic intent from low-level geometric execution, effectively resolving conflicts between text control and spatial constraints in HSI.
* **Latent Semantic Planner:** Developed a conditional multimodal planner encoding textual instructions and local goal voxels into a latent interaction affordance space for robust generalization under conflicting spatial cues.
* **Physics-Regularized Diffusion Executor:** Formulated a physics-regularized denoising objective with differentiable repulsive potential fields, granting the motion generator a natural collision-avoidance reflex without costly test-time optimization.

---
<!-- *For more details, check out our [arXiv Preprint](https://arxiv.org/abs/2607.05787).* -->