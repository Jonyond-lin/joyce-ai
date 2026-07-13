---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

Hi, I'm Joyce. I am a Ph.D. researcher in Data Science and Artificial Intelligence, working on multimodal generative AI. My recent work focuses on long video generation, audio-driven avatar animation, identity-preserving human synthesis, thermal-to-visible face translation. I care about building generation systems that are not only visually strong, but also structurally reliable: coherent over time, controllable through multimodal conditions, and robust enough for real-world creative and interactive applications.


# 🔥 News

- *2026.06*: 🎉 **MTVDiff** accepted in the ECCV 2026!
- *2026.05*: 🎉 Three papers accepted in the ICML 2026. 
- *2025.11*: 🎉 Two co-first author papers accepted in AAAI 2026!
- *2025.10*: 🎉 We proposed **ApoAvatar**, an expressive audio-driven avatar animation project with refocused audio-pose priors.
- *2025.09*: 🎉 **SceneDecorator** accepted in the NeurIPS 2025!
- *2025.02*: 🎉 **HybridGS** accepted in the CVPR 2025!


# 🎯 Research Interests

My research centers on **multimodal generative AI**, especially models that combine visual, audio, identity, motion, and 3D structure.

- **Long Video Generation.** I study hierarchical memory, motion priors, temporal dynamics, and appearance consistency for long-horizon video synthesis. [[DynaMem]](#pub-4) [[OmniShow]](#pub-6)
- **Audio-driven Avatar Animation.** I work on speech-conditioned facial and body motion generation, with an emphasis on expressive motion and audio-visual alignment. [[ApoAvatar]](#pub-1) [[LatentSync]](#pub-2)
- **Identity-preserving Human Generation.** I am interested in keeping human identity consistent across image sequences, stories, and cross-modal generation settings. [[IdentityStory]](#pub-7) [[SceneDecorator]](#pub-9)
- **Cross-spectrum Face Translation.** I explore thermal-to-visible face translation with multimodal conditions and identity-preserving objectives. [[MTVDiff]](#pub-3) [[DiffTV]](#pub-12)
- **Efficient Diffusion.** I study scalable analytical diffusion and coarse-to-fine inference strategies that reduce complexity without losing generation quality. [[Fast and Scalable Analytical Diffusion]](#pub-5)


<span class='anchor' id='publications'></span>

# 📝 Selected Publications

<sub><strong>As first / co-first author:</strong> CVPR ×1 · ICML ×2 · NeurIPS ×1 · ECCV ×2 · AAAI ×2 · ACM MM ×2 — 10 accepted papers.</sub>

<div class='paper-box' id='pub-2'><div class='paper-box-image'><div><img src='images/latentsync.png' alt="LatentSync thumbnail" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[1]** **[LatentSync: Taming Audio-Conditioned Latent Diffusion Models for Lip Sync with SyncNet Supervision](https://arxiv.org/abs/2412.09262)** \| [[project]](https://github.com/bytedance/LatentSync)

<strong>arXiv preprint</strong> · <strong>open-source project</strong> · <span style="color:#14532d;font-weight:700">Core Contributor</span>

- A diffusion-based framework for high-fidelity lip-sync generation supervised by SyncNet for precise audio-visual alignment. The open-source project has <span style="color:#c0392b;font-weight:700">received 5k+ GitHub stars</span>.
</div>
</div>

<div class='paper-box' id='pub-3'><div class='paper-box-image'><div><img src='images/mtvdiff.png' alt="MTVDiff thumbnail" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[2]** **[MTVDiff: Multimodal Conditional Latent Diffusion for Enhanced Thermal-to-Visible Face Translation](#pub-3)**

<strong>ECCV 2026</strong> · <span style="color:#8b1a1a;font-weight:700">CCF-B</span> · <span style="color:#14532d;font-weight:700">Co-first Author</span>

- A multimodal latent diffusion framework that synergistically integrates depth and textual information for thermal-to-visible face translation while preserving identity characteristics.
</div>
</div>

<div class='paper-box' id='pub-4'><div class='paper-box-image'><div><img src='images/dynamem_paper.png' alt="DynaMem thumbnail" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[3]** **[DynaMem: Consistent Long Video Generation via Hierarchical Memory and Motion Priors](#pub-4)**

<strong>ICML 2026</strong> · <span style="color:#8b1a1a;font-weight:700">CCF-A</span> · <span style="color:#14532d;font-weight:700">First Author</span>

- A unified framework for long-horizon video generation that improves coherence, produces more consistent semantics, stronger temporal dynamics, and more stable appearance on long videos.
</div>
</div>

<div class='paper-box' id='pub-5'><div class='paper-box-image'><div><img src='images/fast_and_scalable.png' alt="Analytical diffusion thumbnail" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[4]** **[Fast and Scalable Analytical Diffusion](https://arxiv.org/abs/2602.16498)**

<strong>ICML 2026</strong> · <span style="color:#8b1a1a;font-weight:700">CCF-A</span> · <span style="color:#14532d;font-weight:700">Co-first Author</span>

- A training-free framework that decouples inference complexity from dataset size and uses a coarse-to-fine mechanism to dynamically pinpoint a compact Golden Subset for inference.
</div>
</div>

<div class='paper-box' id='pub-6'><div class='paper-box-image'><div><img src='images/omnishow.png' alt="OmniShow thumbnail" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[5]** **[OmniShow: Orchestrating Multimodal Conditions for Human-Object Interaction Video Generation](https://arxiv.org/abs/2604.11804)**

<strong>ICML 2026</strong> · <span style="color:#8b1a1a;font-weight:700">CCF-A</span> · <span style="color:#14532d;font-weight:700">5th Author, Core Contributor</span>

- An end-to-end framework tailored for Human-Object Interaction video generation that orchestrates multiple multimodal conditions.
</div>
</div>

<div class='paper-box' id='pub-7'><div class='paper-box-image'><div><img src='images/identitystory.png' alt="IdentityStory thumbnail" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[6]** **[IdentityStory: Taming Your Identity-Preserving Generator for Human-Centric Story Generation](https://arxiv.org/abs/2512.23519)**

<strong>AAAI 2026</strong> · <span style="color:#8b1a1a;font-weight:700">CCF-A</span> · <span style="color:#14532d;font-weight:700">Co-first Author</span>

- A framework for human-centric story generation that ensures consistent character identity across sequential images.
</div>
</div>

<div class='paper-box' id='pub-8'><div class='paper-box-image'><div><img src='images/fdp.png' alt="FDP thumbnail" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[7]** **[FDP: A Frequency-Decomposition Preprocessing Pipeline for Unsupervised Anomaly Detection in Brain MRI](https://arxiv.org/abs/2511.12899)**

<strong>AAAI 2026</strong> · <span style="color:#8b1a1a;font-weight:700">CCF-A</span> · <span style="color:#14532d;font-weight:700">Co-first Author</span>

- The first unsupervised anomaly detection method to leverage frequency-domain reconstruction for simultaneous pathology suppression and anatomical preservation in brain MRI.
</div>
</div>

<div class='paper-box' id='pub-1'><div class='paper-box-image'><div><img src='images/apoavatar.png' alt="ApoAvatar thumbnail" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[8]** **[ApoAvatar: Expressive Audio-Driven Avatar Generation via Refocused Audio-Pose Priors](https://openreview.net/forum?id=9fw3g2jFbc)**

<strong>In Review</strong> · <span style="color:#14532d;font-weight:700">First Author</span>

- A diffusion-based avatar generation framework that ties speaking style to expressive motion dynamics through refocused audio-pose priors.
</div>
</div>

<div class='paper-box' id='pub-9'><div class='paper-box-image'><div><img src='images/scenedecorator_paper.png' alt="SceneDecorator thumbnail" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[9]** **[SceneDecorator: Towards Scene-Oriented Story Generation with Scene Planning and Scene Consistency](https://arxiv.org/abs/2510.22994)**

<strong>NeurIPS 2025</strong> · <span style="color:#8b1a1a;font-weight:700">CCF-A</span> · <span style="color:#14532d;font-weight:700">Co-first Author, Project Leader</span>

- A scene-level generative framework that enhances narrative coherence through explicit scene planning and scene consistency.
</div>
</div>

<div class='paper-box' id='pub-10'><div class='paper-box-image'><div><img src='images/hybridgs_paper.png' alt="HybridGS thumbnail" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[10]** **[HybridGS: Decoupling Transients and Statics with 2D and 3D Gaussian Splatting](https://arxiv.org/abs/2412.03844)**

<strong>CVPR 2025</strong> · <span style="color:#8b1a1a;font-weight:700">CCF-A</span> · <span style="color:#14532d;font-weight:700">First Author</span>

- A hybrid representation that models transient objects with per-image 2D Gaussians while maintaining 3D Gaussians for the static scene.
</div>
</div>

<div class='paper-box' id='pub-11'><div class='paper-box-image'><div><img src='images/posemap.png' alt="PoseMap thumbnail" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[11]** **[Learning Neural Volumetric Pose Features for Camera Localization](https://arxiv.org/abs/2403.12800)**

<strong>ECCV 2024</strong> · <span style="color:#8b1a1a;font-weight:700">CCF-B</span> · <span style="color:#14532d;font-weight:700">First Author</span>

- Introduces PoseMap, a neural volumetric pose feature that enhances camera localization by encapsulating the information between images and their associated camera poses.
</div>
</div>

<div class='paper-box' id='pub-12'><div class='paper-box-image'><div><img src='images/difftv.png' alt="Diff TV thumbnail" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[12]** **[DiffTV: Identity-preserved Thermal-to-Visible Face Translation via Feature Alignment and Dual-Stage Conditions](https://dl.acm.org/doi/10.1145/3664647.3680635)**

<strong>ACM MM 2024</strong> · <span style="color:#8b1a1a;font-weight:700">CCF-A</span> · <span style="color:#14532d;font-weight:700">First Author</span>

- A dual-stage image translation framework that transforms infrared faces into realistic visible-light faces while preserving identity characteristics.
</div>
</div>

<div class='paper-box' id='pub-13'><div class='paper-box-image'><div><img src='images/scenetextdetector.png' alt="Scene text detection thumbnail" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[13]** **[An End-to-End Scene Text Detector with Dynamic Attention](https://dl.acm.org/doi/10.1145/3551626.3564980)**

<strong>ACM MM 2023</strong> · <span style="color:#8b1a1a;font-weight:700">CCF-A</span> · <span style="color:#14532d;font-weight:700">First Author</span>

- A dynamic end-to-end framework that generates a deformable, dynamic view for multi-oriented and curved text instances.
</div>
</div>


# 🎓 Education
- *2023 - 2027*, Ph.D. in Data Science and Artificial Intelligence, Monash University.
- *2020 - 2023*, M.Sc. in Computer Science, Xiamen University.
- *2016 - 2020*, B.Sc. in Computer Science, Xiamen University.


# 💻 Research Experience

<div class='paper-box'><div class='paper-box-image'><div><img src='https://commons.wikimedia.org/wiki/Special:FilePath/ByteDance_logo_English.svg' alt="ByteDance logo" style="max-width:100%;max-height:64px;height:auto;display:block;margin:0 auto;"></div></div>
<div class='paper-box-text' markdown="1">

**Audio-driven Avatar Animation**

- Research intern working on expressive speech-conditioned facial and body motion generation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='https://commons.wikimedia.org/wiki/Special:FilePath/AMD_Logo.svg' alt="AMD logo" style="max-width:100%;max-height:64px;height:auto;display:block;margin:0 auto;"></div></div>
<div class='paper-box-text' markdown="1">

**Cross-Modal Joint Generation**

- Research intern developing multimodal synthesis methods that connect visual and auditory representations.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/logo-horizon.png' alt="Horizon Robotics logo" style="max-width:100%;max-height:64px;height:auto;display:block;margin:0 auto;"></div></div>
<div class='paper-box-text' markdown="1">

**Image-to-Image Translation**

- Research intern working on cross-spectrum facial synthesis (thermal-to-visible face translation).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='https://commons.wikimedia.org/wiki/Special:FilePath/Tencent_logo_2017.svg' alt="Tencent logo" style="max-width:100%;max-height:64px;height:auto;display:block;margin:0 auto;"></div></div>
<div class='paper-box-text' markdown="1">

**Scene Text Detection**

- Research intern working on robust text detection and recognition in complex natural environments.
</div>
</div>
