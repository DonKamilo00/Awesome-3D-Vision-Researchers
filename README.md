# Awesome Dynamic Scene Reconstruction 🌌

A curated and strictly classified list of prominent research labs, top-tier academic institutions, and industry powerhouse teams focusing purely on **Dynamic Scene Reconstruction**, **4D Novel View Synthesis**, **Dynamic 3D Gaussian Splatting**, and **4D World Models**.

## 📑 Table of Contents
-[Strict Classifications in 4D Vision](#strict-classifications-in-4d-vision)
-[Industry Heavyweights & Elite Teams](#industry-heavyweights--elite-teams)
  - [NVIDIA Research](#nvidia-research)
  - [ByteDance AI Lab & PICO](#bytedance-ai-lab--pico-mr)
  - [Meta Reality Labs](#meta-reality-labs)
  -[Google DeepMind & Google Research](#google-deepmind--google-research)
- [Top Academic Institutions & Labs](#top-academic-institutions--labs)
- [Key Workshops & Communities](#key-workshops--communities)

---

## 🔬 Strict Classifications in 4D Vision
To effectively source leads, research teams in this repo are strictly classified into the following sub-domains of dynamic scene reconstruction:
1. **Dynamic/Deformable 3D Gaussian Splatting (4D-GS):** Real-time rendering and tracking of dynamic elements using warp fields or topology compactness.
2. **Space-Time Neural Radiance Fields (Dynamic NeRFs):** Optimizing implicit 3D representations over a temporal axis from monocular or multi-view videos.
3. **4D World Models & Physical Simulation:** Generative 3D foundation models that reconstruct physically accurate and interactable dynamic environments.
4. **Feed-Forward 4D Reconstruction:** Utilizing cross-attention and diffusion priors to generate dynamic 3D scenes in a single forward pass without per-scene optimization.

---

## 🏢 Industry Heavyweights & Elite Teams

### [NVIDIA Research](https://research.nvidia.com/)
NVIDIA is an undisputed leader in accelerating neural rendering, focusing heavily on real-time physics and dynamic compression. 
* **Real-Time Graphics Research Group:** Led by researchers like Aaron Lefohn and Benedikt Bitterli, this team is responsible for redefining the future of photoreal, real-time dynamic computer graphics by combining advances in light simulation and AI.
* **Dynamic Media Streaming AI (QUEEN):** Led by Shalini De Mello, this team recently introduced **QUEEN**—an optimized model for fast, efficient dynamic scene reconstruction. It tracks and reuses static rendering regions to support low-bandwidth, high-quality 3D video conferencing and teleoperation streaming.
* **High-Fidelity Neural Reconstruction:** Driven by Ming-Yu Liu, the team behind **Neuralangelo** translates 2D videos into meticulously detailed 3D structures and dynamic digital twins. Researchers like Xuan Li actively investigate 3D generation combined with physics-based simulation. 

### [ByteDance AI Lab & PICO MR](https://research.bytedance.com/)
ByteDance has heavily invested in 4D generation and large-scale scene understanding to power their AR/VR (PICO) ecosystems and TikTok/Douyin filters.
* **PICO MR (Mixed Reality) Team:** A dedicated perception team pushing the boundaries of 3D environment perception. They focus on multimodal scene understanding, large-scale 3D scene reconstruction (3DGS, NeRF), and AIGC-based scene generation to deploy real-world MR capabilities.
* **Seed3D Project (ByteDance Seed):** Led by researchers such as Jianfeng Zhang, this highly specialized team builds **4D World Models** through generative 3D foundation models. Their goal is capturing not just the geometry and appearance of a dynamic scene, but its temporal dynamics and physics (e.g., AvatarGen, GP-NeRF). 
* **Core Technologies:** ByteDance researchers are behind major breakthroughs like **Gen3R** (bridging foundational reconstruction with video diffusion) and **MVDream** (multi-view diffusion for high-quality 3D generation).

###[Meta Reality Labs (MRL)](https://research.facebook.com/augmented-reality-virtual-reality/)
Meta's efforts are primarily geared toward photorealistic teleportation, Codec Avatars, and dynamic room-scale scanning.
* **Dynamic Rendering & Telepresence:** Researchers like Christian Richardt and Peter Kontschieder lead efforts in high-fidelity view synthesis and dynamic reconstruction (e.g., HyperReel, Neural Duplex Radiance Fields).
* **Deformable Gaussians & Pre-scanned Dynamics:** Denis Rozumny works extensively on dynamic scene reconstruction, notably co-authoring **DRoPS** (Dynamic 3D Reconstruction of Pre-Scanned Objects) and **Free-Range Gaussians**.
* **Text-Guided & Feed-Forward 3D:** Numair Khan contributes significantly to predicting deformable 3D Gaussian splats from monocular videos and text-guided 3D scene editing.

### [Google DeepMind & Google Research](https://deepmind.google/)
Google bridges the gap between raw optical flow tracking and generative video models for 4D perception.
* **D4RT (Dynamic 4D Reconstruction and Tracking):** A dedicated DeepMind initiative aiming to solve the inverse problem of recovering volumetric 3D in motion from flat 2D video sequences, essentially granting AI a mental model of dynamic physical realities. 
* **DynIBaR (Google Research & Cornell):** A revolutionary framework for Neural Dynamic Image-Based Rendering. It overcomes the struggle of unregulated camera trajectories and complex object motions in monocular videos, generating highly realistic free-viewpoint renderings.
* **CAT4D & PhysWorld:** DeepMind researchers actively push the boundary of 4D novel view synthesis (CAT4D) and are integrating 4D dynamic reconstructions with robotic learning via physical world modeling (PhysWorld).

---

## 🏫 Top Academic Institutions & Labs

* **Max Planck Institute (MPI) for Informatics / Intelligent Systems (Germany)** 🇩🇪
  * **Graphics, Vision, & Video Group:** Led by Prof. Christian Theobalt, MPI is a historic pioneer in marker-less motion capture and algorithmic 4D surface reconstruction.
  * *Notable Tech:* **NeuS2**—a fast neural implicit surface framework capable of dynamic scene reconstruction from multi-view videos in seconds, utilizing incremental training strategies for moving topologies.
* **Brown University - Interactive 3D Vision Lab (USA)** 🇺🇸
  * Led by Prof. Srinath Sridhar, focusing heavily on object-centric dynamic scene reconstructions and organizing major 4D World Model conferences.
* **Carnegie Mellon University (CMU) (USA)** 🇺🇸
  * Working alongside Fujitsu Research, CMU researchers recently solved 3D scene reconstruction *without camera motion* by adapting classical Lucas-Kanade optical flow directly into the warp field of Dynamic Gaussian Splatting.
* **National University of Singapore (NUS) - Show Lab (Singapore)** 🇸🇬
  * Deeply invested in multi-modal 4D dynamic human-object-scene reconstruction and editing for robotic perception and VR.

---

## 🗓️ Key Workshops & Communities
To stay up to date on networking and open-source releases, these are the flagship sub-communities:
* **[DynaVis](https://dynavis.github.io/):** The International Workshop on Dynamic Scene Reconstruction, frequently held at CVPR, focusing on 4D data acquisition, dynamic digital humans, and non-rigid structure from motion.
* **[4D World Models Workshop](https://4d-world-models.github.io/):** Held at CVPR, bridging reconstruction and generation. It covers temporal coherence, efficient rendering, and physical simulations of dynamic worlds, featuring organizers from Meta Reality Labs, DeepMind, and top universities.
