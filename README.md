# Awesome Dynamic Scene Reconstruction 🌌

A curated and strictly classified list of prominent research labs, top-tier academic institutions, and industry powerhouse teams focusing purely on **Dynamic Scene Reconstruction**, **4D Novel View Synthesis**, **Dynamic 3D Gaussian Splatting**, and **4D World Models**.

## 📑 Table of Contents
- [Strict Classifications in 4D Vision](#-strict-classifications-in-4d-vision)
- [Industry Heavyweights & Elite Teams](#-industry-heavyweights--elite-teams)
-[Top Academic Institutions & Labs](#-top-academic-institutions--labs)
- [Key Workshops & Communities](#-key-workshops--communities)

---

## 🔬 Strict Classifications in 4D Vision

To effectively source leads, research teams and their technologies in this repo are strictly classified into the following sub-domains:

| Classification | Description |
| :--- | :--- |
| **Dynamic/Deformable 3D Gaussian Splatting (4D-GS)** | Real-time rendering and tracking of dynamic elements using warp fields, deformation MLPs, or topology compactness. |
| **Space-Time Neural Radiance Fields (Dynamic NeRFs)** | Optimizing implicit 3D representations over a temporal axis from monocular or multi-view videos. |
| **4D World Models & Physical Simulation** | Generative 3D foundation models that reconstruct physically accurate and interactable dynamic environments over time. |
| **Feed-Forward 4D Reconstruction** | Utilizing cross-attention and diffusion priors to generate dynamic 3D scenes in a single forward pass without per-scene optimization. |

---

## 🏢 Industry Heavyweights & Elite Teams

### [NVIDIA Research](https://research.nvidia.com/)
| Team / Division | Key Researchers | Focus Areas & Notable Technologies |
| :--- | :--- | :--- |
| **Real-Time Graphics Research** | Aaron Lefohn, Benedikt Bitterli | Redefining photoreal, real-time dynamic computer graphics; combining advanced light simulation with AI. |
| **Dynamic Media Streaming AI** | Shalini De Mello | Introduced **QUEEN**, an optimized model for fast dynamic scene reconstruction and low-bandwidth, high-quality 3D video streaming. |
| **High-Fidelity Neural Recon.** | Ming-Yu Liu, Xuan Li | **Neuralangelo** (translating 2D videos to highly detailed 3D structures); combining 3D generation with physics-based simulations. |

### [ByteDance AI Lab & PICO](https://research.bytedance.com/)
| Team / Division | Key Researchers | Focus Areas & Notable Technologies |
| :--- | :--- | :--- |
| **PICO MR (Mixed Reality)** | *PICO Perception Team* | Multimodal scene understanding, large-scale 3DGS/NeRF reconstruction, and AIGC-based dynamic scene generation for AR/VR. |
| **Seed3D Project** | Jianfeng Zhang | Building **4D World Models** (AvatarGen, GP-NeRF) to capture geometry, appearance, temporal dynamics, and physical interactions. |
| **Core Technologies** | *ByteDance AI Researchers* | **Gen3R** (bridging foundational reconstruction with video diffusion); **MVDream** (multi-view diffusion for high-quality 3D generation). |

###[Meta Reality Labs (MRL)](https://research.facebook.com/augmented-reality-virtual-reality/)
| Team / Division | Key Researchers | Focus Areas & Notable Technologies |
| :--- | :--- | :--- |
| **Dynamic Rendering** | Christian Richardt, Peter Kontschieder | High-fidelity novel view synthesis and dynamic reconstruction (e.g., **HyperReel**, Neural Duplex Radiance Fields). |
| **Deformable Gaussians** | Denis Rozumny | Pre-scanned dynamics; co-authored **DRoPS** (Dynamic 3D Reconstruction of Pre-Scanned Objects) and **Free-Range Gaussians**. |
| **Text-Guided & Feed-Forward 3D** | Numair Khan | Predicting deformable 3D Gaussian splats from monocular videos; text-guided 4D scene editing. |

### [Google DeepMind & Google Research](https://deepmind.google/)
| Team / Division | Affiliation | Focus Areas & Notable Technologies |
| :--- | :--- | :--- |
| **D4RT Initiative** | DeepMind | **Dynamic 4D Reconstruction and Tracking:** Solving inverse problems to recover volumetric 3D in motion from flat 2D video sequences. |
| **DynIBaR** | Google Research & Cornell | Neural Dynamic Image-Based Rendering; generating realistic free-viewpoint renderings from videos with unregulated camera/object motion. |
| **CAT4D & PhysWorld** | DeepMind | Pushing 4D novel view synthesis (**CAT4D**) and integrating 4D dynamic reconstructions with robotic learning via world modeling (**PhysWorld**). |

---

## 🏫 Top Academic Institutions & Labs

| Institution | Location | Lab / Group | Key Leaders | Focus Areas & Notable Contributions |
| :--- | :--- | :--- | :--- | :--- |
| **Max Planck Institute (MPI)** | 🇩🇪 Germany | Graphics, Vision, & Video Group | Prof. Christian Theobalt | Pioneer in marker-less MoCap; created **NeuS2** (fast neural implicit surface framework for dynamic multi-view videos). |
| **Brown University** | 🇺🇸 USA | Interactive 3D Vision Lab | Prof. Srinath Sridhar | Object-centric dynamic reconstructions; organizers of the primary 4D World Model conferences. |
| **Carnegie Mellon Univ. (CMU)** | 🇺🇸 USA | CMU & Fujitsu Research | *Joint Research Team* | Solved 3D scene reconstruction *without camera motion* by adapting Lucas-Kanade optical flow into Dynamic 3DGS warp fields. |
| **National Univ. of Singapore** | 🇸🇬 Singapore | Show Lab | *Show Lab Researchers*| Multi-modal 4D dynamic human-object-scene reconstruction and editing for robotic perception and VR. |

---

## 🗓️ Key Workshops & Communities

To stay up to date on networking, open-source releases, and the latest papers, track these flagship sub-communities:

| Workshop / Community | Host Conference | Core Focus & Description |
| :--- | :--- | :--- |
| **[DynaVis](https://dynavis.github.io/)** | CVPR | The International Workshop on Dynamic Scene Reconstruction; focuses on 4D data acquisition, dynamic digital humans, and non-rigid structure from motion. |
| **[4D World Models Workshop](https://4d-world-models.github.io/)** | CVPR | Bridges reconstruction and generation; covers temporal coherence, efficient rendering, and physical simulations of dynamic worlds. |
