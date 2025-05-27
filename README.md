# SALSA-RL: Stability Analysis in the Latent Space of Actions for Reinforcement Learning [[arXiv]](https://arxiv.org/abs/2502.15512)

```BibTex
@article{li2025salsa,
  title={SALSA-RL: Stability Analysis in the Latent Space of Actions for Reinforcement Learning},
  author={Li, Xuyang and Maulik, Romit},
  journal={arXiv preprint arXiv:2502.15512},
  year={2025}
}
```

## Overview
SALSA-RL is a reinforcement learning framework that non-invasively analyzes local stability in the latent action space. By modeling actions as time-varying linear dynamics, it applies control-theoretic tools, such as spectral radius, transient growth, and Floquet analysis, for stability analysis. SALSA-RL enables interpretation of pretrained agents, early warning of control failures, and insight into policy behavior without modifying the policy or training process, and with no loss in performance.


## Local stability animations for LunarLander (hovering objective)
### Case 1
<src="assets/video-case-1.mp4" width="40%">
<src="assets/animation-case-1.gif" width="600"/>

### Case 2
<div style="display: flex; align-items: center; gap: 1rem;">
  <video width="33%" controls>
    <source src="assets/video-case-2.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <img src="assets/animation-case-2.gif" style="width: 66%;">
</div>

### Case 3
<div style="display: flex; align-items: center; gap: 1rem;">
  <video width="33%" controls>
    <source src="assets/video-case-3.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <img src="assets/animation-case-3.gif" style="width: 66%;">
</div>

### Case 4
<div style="display: flex; align-items: center; gap: 1rem;">
  <video width="33%" controls>
    <source src="assets/video-case-4.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <img src="assets/animation-case-4.gif" style="width: 66%;">
</div>

