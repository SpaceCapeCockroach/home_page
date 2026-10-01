---
title: "Vision-Language Mapping & 3D Grounding via Hashgrid and SDF Feature Fusion"
collection: publications
category: manuscripts
permalink: /publication/2026-09-28-vlm-3d-mapping
excerpt: 'This paper presents a hashgrid-based framework projecting 2D VLM features into 3D space for real-time online semantic mapping and 3D grounding.'
date: 2026-09-28
status: under_review
venue: 'Under Review at IJRR (arXiv preprint arXiv:2609.38620)'
paperurl: 'https://arxiv.org/abs/2609.38620'
# citation: 'Hanwen Cao, <b>Wenqiang Wu</b>, et al. (2026). &quot;Vision-Language Mapping & 3D Grounding via Hashgrid and SDF Feature Fusion.&quot; <i>arXiv:2609.38620</i>.'
---

### Abstract
This work introduces a novel hybrid semantic-geometric pipeline for real-time, open-vocabulary 3D semantic mapping and grounding. By integrating a hashgrid-based feature projection model with Signed Distance Fields (SDF) and pre-trained DETR-style decoders (Locate-3D), the system enables fast text-prompted 3D query, accurate submap alignment, and robust pose estimation in complex indoor environments.

### Key Contributions
* **Hashgrid 3D Projection:** Developed a high-performance hashgrid-based framework for projecting 2D Vision-Language Model (VLM) features into dynamic 3D representations.
* **Open-Vocabulary Grounding:** Integrated a DETR-style 3D decoder allowing natural-language spatial queries without fixed closed-set categories.
* **Semantic-Geometric Fusion:** Combined SDF representation with high-level VLM features to refine submap alignment and improve camera pose estimation on ScanNet benchmarks.

---
*For more details, check out our [arXiv Preprint](https://arxiv.org/abs/2609.38620) or visit the [Existential Robotics Lab](https://existentialrobotics.org/HIGS_webpage/) page.*