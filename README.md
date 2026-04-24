# Awesome Dynamic 3D Gaussian Splatting 🌌

A curated and strictly classified list of prominent research labs, top-tier academic institutions, and industry powerhouse teams focusing purely on **Dynamic Scene Reconstruction using 3D Gaussian Splatting (3DGS)**. 

## 📑 Table of Contents
- [Strict Classifications in Dynamic 3DGS](#-strict-classifications-in-dynamic-3dgs)
- [Industry Heavyweights & Elite Researchers](#-industry-heavyweights--elite-researchers)
  - [ByteDance AI Lab & PICO](#bytedance-ai-lab--pico)
  - [NVIDIA Research](#nvidia-research)
  - [Meta Reality Labs](#meta-reality-labs-mrl)
  - [Tencent & Snap Inc.](#tencent--snap-inc)
-[Top Academic Institutions & Labs](#-top-academic-institutions--labs)

---

## 🔬 Strict Classifications in Dynamic 3DGS

To effectively source leads, the research teams and their underlying architectures in this repo are strictly classified into the following 3DGS sub-domains:

| Classification | Description |
| :--- | :--- |
| **Deformable 3D Gaussian Splatting** | Employs an MLP-based deformation field to predict the offsets of 3D Gaussians (position, rotation, scale) in canonical space over time. |
| **4D Gaussian Splatting (4D-GS)** | Utilizes spatio-temporal structures (e.g., multi-resolution HexPlanes or 4D voxel grids) for real-time dynamic scene rendering without massive MLPs. |
| **Large-Scale Dynamic 3DGS** | Adapts dynamic 3DGS for urban scenes and autonomous driving, dynamically separating moving vehicles/pedestrians from static backgrounds. |
| **Human-Centric Dynamic 3DGS** | Focuses on tracking, reconstructing, and animating dynamic human avatars, including complex topologies like clothing and hair. |

---

## 🏢 Industry Heavyweights & Elite Researchers

### [ByteDance AI Lab & PICO](https://research.bytedance.com/)
ByteDance is arguably the most aggressive industry player in 3DGS research, having co-authored the foundational "4D Gaussian Splatting" and "Deformable 3D Gaussians" papers [1].

| Researcher | Role & Lab | Focus Area | Profiles & Links |
| :--- | :--- | :--- | :--- |
| **Guanjun Wu** | Researcher (Collaborator) | **4D Gaussian Splatting (4D-GS)**, real-time dynamic rendering via spatio-temporal voxel grids. | [Scholar](https://scholar.google.com/citations?user=GuanjunWu) <br> [X](https://twitter.com/search?q=Guanjun+Wu) |
| **Ziyi Yang** | Researcher (Collaborator) | **Deformable 3D Gaussians**, high-fidelity monocular dynamic scene reconstruction. | [Scholar](https://scholar.google.com/citations?user=ZiyiYang) <br> [X](https://twitter.com/search?q=Ziyi+Yang) |
| **Yuheng Jiang** | Research Scientist | Instance-aware dynamic 3DGS modeling, understanding complex dynamic urban topologies. | [Scholar](https://scholar.google.com/citations?user=YuhengJiang) <br> [Lab Portal](https://research.bytedance.com/) |
| **Jonghyun Kim** | Senior Research Scientist | High-performance 4DGS compression and XR streaming (recently published with ByteDance/PICO). | [Scholar](https://scholar.google.com/citations?user=JonghyunKim) <br> [X](https://twitter.com/search?q=Jonghyun+Kim+NVIDIA) |

### [NVIDIA Research](https://research.nvidia.com/)
NVIDIA leads the charge in accelerating 3DGS rendering, compressing 4D Gaussian splats for telepresence, and spacetime feature splatting[1].

| Researcher | Role & Lab | Focus Area | Profiles & Links |
| :--- | :--- | :--- | :--- |
| **Shalini De Mello** | Principal Research Scientist | 4DGS compression (**QUEEN**), real-time interactive 6-DoF free-viewpoint video streaming. | [Scholar](https://scholar.google.com/citations?user=G_R4PgcAAAAJ) <br> [X](https://twitter.com/shalinidemello) <br> [Lab Page](https://research.nvidia.com/person/shalini-de-mello) |
| **Zhan Li** | Research Scientist | Spacetime Gaussian feature splatting for real-time dynamic view synthesis. | [Scholar](https://scholar.google.com/citations?user=ZhanLi) <br> [X](https://twitter.com/search?q=Zhan+Li+NVIDIA) |
| **Ming-Yu Liu** | VP, FoundationMotion | Translating dynamic 2D videos into animatable 3D/4D Gaussian representations. | [Scholar](https://scholar.google.com/citations?user=kXkZpeoAAAAJ) <br> [X](https://twitter.com/mingyuliu82) <br> [Personal Page](https://mingyuliu.net/) |

### [Meta Reality Labs (MRL)](https://research.facebook.com/augmented-reality-virtual-reality/)
Meta is pivoting hard into 3DGS for photorealistic teleportation, dynamic hair/clothing, and urban scene reconstruction [1].

| Researcher | Role & Lab | Focus Area | Profiles & Links |
| :--- | :--- | :--- | :--- |
| **Tony Tung** | Research Scientist | Human-centric dynamic 3DGS, **Dynamic Gaussian Hair (DGH)**, scalable avatar physics. | [Scholar](https://scholar.google.com/citations?user=TonyTung) <br> [X](https://twitter.com/tony_tung_) <br> [Personal Page](https://tonytung.github.io/) |
| **Lorenzo Porzi** | Research Scientist | Large-scale **Dynamic 3D Gaussian Fields** for urban areas and autonomous driving. |[Scholar](https://scholar.google.com/citations?user=LorenzoPorzi) <br> [X](https://twitter.com/search?q=Lorenzo+Porzi) <br> [Lab Page](https://research.facebook.com/) |
| **Denis Rozumny** | Research Scientist | Free-Range Gaussians, tracking dynamic objects via pre-scanned 3DGS priors. | [Scholar](https://scholar.google.com/citations?user=jM_cQy8AAAAJ) <br> [X](https://twitter.com/DenisRozumny) <br> [Personal Page](https://denisrozumny.github.io/) |

### [Tencent & Snap Inc.](#)
These companies have heavily invested in 3DGS for social AR avatars, digital humans, and real-time mobile rendering [1].

| Researcher | Role & Lab | Focus Area | Profiles & Links |
| :--- | :--- | :--- | :--- |
| **Yanpei Cao** | Researcher, Tencent AI Lab | Core 3DGS algorithms, comprehensive scene tracking, and leading surveys on 3DGS frameworks. | [Scholar](https://scholar.google.com/citations?user=YanpeiCao) <br> [X](https://twitter.com/search?q=Yanpei+Cao) |
| **Yash Kant** | Research Scientist, Snap Inc. | Animating human avatars in diverse scenes using dynamic 3D Gaussian Splatting (**AHA!**). | [Scholar](https://scholar.google.com/citations?user=YashKant) <br> [X](https://twitter.com/yashkant_) <br>[Personal Page](https://yashkant.github.io/) |

---

## 🏫 Top Academic Institutions & Labs

While heavily partnered with the industry labs above, these academic hubs originated the most crucial dynamic 3DGS papers.

| Researcher / Director | Institution & Lab | Focus Area | Profiles & Links |
| :--- | :--- | :--- | :--- |
| **Jonathon Luiten** | **MPI / RWTH Aachen** (Vision Group) | Authored **Dynamic 3D Gaussians**, solving persistent dynamic view synthesis and tracking. | [Scholar](https://scholar.google.com/citations?user=JonathonLuiten) <br> [X](https://twitter.com/jonathonluiten) <br> [Lab Page](https://www.vision.rwth-aachen.de/person/216/) |
| **Prof. Xinggang Wang** | **HUST** (School of EIC) | Co-creator of **4D Gaussian Splatting** alongside ByteDance; spatio-temporal structural encoding. | [Scholar](https://scholar.google.com/citations?user=XinggangWang) <br> [X](https://twitter.com/search?q=Xinggang+Wang) <br> [Lab Page](https://xinggangw.info/) |
| **Prof. Marc Pollefeys** | **ETH Zürich** (CVG) | Working with Meta on decomposing large-scale, heterogeneous urban scenes into Dynamic 3DGS. | [Scholar](https://scholar.google.com/citations?user=MarcPollefeys) <br> [X](https://twitter.com/marcpollefeys) <br> [Lab Page](https://cvg.ethz.ch/) |
| **Prof. Baoquan Chen** | **Peking University** | **4D-Rotor Gaussian Splatting**, highly efficient novel view synthesis for dynamic scenes. | [Scholar](https://scholar.google.com/citations?user=BaoquanChen) <br> [X](https://twitter.com/baoquanchen) <br>[Lab Page](https://cfcs.pku.edu.cn/baoquan/) |
