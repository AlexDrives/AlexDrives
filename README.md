<h1 align="center">Hi, I'm Junhao (Alex) Liu · 刘俊豪 👋</h1>

<h3 align="center">Embodied AI · Real2Sim & World Representations · VLA · Robot Learning</h3>

<p align="center">
  <strong>English</strong> | <a href="README.zh-CN.md">简体中文</a>
</p>

<p align="center">
  <a href="https://portfolio-rouge-three-eznvbawdug.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-junhao.liu-111111?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://portfolio-rouge-three-eznvbawdug.vercel.app/Junhao_Liu_CV.pdf"><img src="https://img.shields.io/badge/CV-PDF-333333?style=for-the-badge&logo=readthedocs&logoColor=white" alt="CV PDF" /></a>
  <a href="https://portfolio-rouge-three-eznvbawdug.vercel.app/#contact"><img src="https://img.shields.io/badge/Email_Routing-3_Inboxes-1F2937?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Routing" /></a>
</p>
<p align="center">
  <a href="mailto:whichAlex@sjtu.edu.cn"><code>Academic · whichAlex@sjtu.edu.cn</code></a> ·
  <a href="mailto:junhao.liu@cn.abb.com"><code>ABB R&amp;D · junhao.liu@cn.abb.com</code></a> ·
  <a href="mailto:alex20160117@gmail.com"><code>Personal · alex20160117@gmail.com</code></a>
</p>

---

### About Me

🎓 **B.E. in Intelligent Perception Engineering** @ **Shanghai Jiao Tong University** *(Class of 2027 · Junior Major GPA `89.5/100`, Perception Systems `100/100` Rank `1/38`)*  
🔬 **Environment Reasoning R&D Intern** @ **ABB Robotics** — building automated **Real2Sim** asset pipelines (`SimFoundry` × `OmniGibson`), CAD-inspired **Port–Mate** $SE(3)$ scene representations, and solver-backed **LangGraph + Critic** simulation agents  
🤖 Previously **Robotics Algorithm Intern** @ **ShareTronic** — quadruped RL visual navigation (`NavRL` in `NVIDIA Isaac Lab / Sim`), `ROS2` sim-to-real diagnostics on **Unitree Go2**, and `VGGT` egocentric navigation data R&D  
🧭 **Research Thesis**: Bridging **explicit 3D geometric/physical constraints** with **scalable robot learning** — from verifiable Real2Sim scene harnesses to real-robot **VLA post-training & System-2/1 execution**  
📬 Seeking **2027 Fall PhD / Research Graduate Opportunities** in Embodied AI, Robot Learning, Real2Sim2Real & Physical World Models  

---

## Research & Systems Highlights

- 🏆 **[Ant LingBot Embodied AI Challenge (`LingBot-VLA 2.0 6B`)](https://github.com/AlexDrives/lingbot-competiton-fbfyfbf)** — Initiated our 5-undergrad team (`fbfyfbf`). Ranked **6th / 1,855** in RoboTwin 2.0 50-task simulation prelims (`82.22%` clean / `57.26%` randomized; resolved action-quantile shift, built phase-preserving Fourier augmentation & paired sign-test eval). Earned the **Finals Excellence Award** in the **48-hour AgileX Cobot Magic bimanual real-robot hackathon**: led teleop & zero-jerk `200 Hz` DAgger takeover pipelines (`646` demos), co-built streaming multi-GPU training + **train-time / async Real-Time Chunking (RTC)** on a 16 GB GPU, and co-developed a DeepSeek **System-2 subtask harness** + `205k`-param wrist grasp CNN (`99.8%` held-out accuracy) with a full Round-3 data-drift post-mortem.
- 🧩 **[Real2Sim & Port–Mate Terminal-State Reasoning @ ABB Robotics](https://portfolio-rouge-three-eznvbawdug.vercel.app/#experience/abb)** — Formulated natural-language scene construction as verifiable `Port–Mate` $SE(3)$ assembly solving ($T_i = T_b L_b M(\theta) L_i^{-1}$, $S_{\text{op}} \xrightarrow{\text{OmniGibson}} S_{\text{evo}}$) across `on`, `seat`, `insert`, `in`, `free_in`, and `joint` predicates, paired with a 6-stage USD physics gate (`89/89` acceptance suite) and independent-oracle geometric support discovery (`0.979` precision).
- 🐕 **[Quadruped RL Navigation & Sim2Real Diagnostics @ ShareTronic](https://portfolio-rouge-three-eznvbawdug.vercel.app/#experience/sharetronic)** — Migrated and adapted UAV `NavRL` to a 12-DoF **Unitree Go2** in `NVIDIA Isaac Lab`, suppressed crab-walking via gait-aware reward shaping & domain randomization, isolated real-robot dynamic-obstacle lag to `ROS2` occupancy-map updates, and prototyped `VGGT + DINO` egocentric human walking trajectory extraction.
- 🧬 **[RNA-GCP-VQVAE](https://github.com/AlexDrives/RNA-GCP-VQVAE)** — $SE(3)$-equivariant geometric representation learning extending protein `GCP-VQVAE` to **RNA 3D backbone tokenization & reconstruction**: homology-controlled `RNAsolo / cd-hit-est (c80) → HDF5` pipeline, 6-torsion dihedral frames, and an **AlphaFold2-style IPA decoder** under trajectory-level **FAPE** supervision (`1.08 Å` MAE · `0.79` TM-score).
- 🎲 **[Autonomous Robotic Dice Stacking](https://github.com/AlexDrives/Dice-detection-and-auto-stacking-with-OpenMV-and-OpenCV)** — End-to-end lens undistortion, dense 27-dice single-view perception, homography + quadratic-residual calibration (`450+` pairs, `0.740 mm` mean error), and 4-DOF suction-arm execution (**6 dice in 26s · Rank 1 / 38** at SJTU) · ♠️ **[Kuhn Poker: Self-Play RL vs. CFR](https://github.com/AlexDrives/kuhn_poker-exp)** — Diagnosed policy oscillation in PyTorch self-play REINFORCE against OpenSpiel `CFR / CFR+` exploitability convergence.

---

## Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-283593?style=for-the-badge&logo=c&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-B8450F?style=for-the-badge&logoColor=white)

### Embodied AI, Simulation & Robotics
![NVIDIA Isaac Sim](https://img.shields.io/badge/NVIDIA_Isaac_Sim_%2F_Lab-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![OmniGibson](https://img.shields.io/badge/OmniGibson-1F2937?style=for-the-badge&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![VLA](https://img.shields.io/badge/VLA_Post--Training_%26_RTC-D97706?style=for-the-badge&logoColor=white)
![Real2Sim](https://img.shields.io/badge/Real2Sim_%26_OpenUSD-0F766E?style=for-the-badge&logoColor=white)
![RoboTwin](https://img.shields.io/badge/RoboTwin_2.0-334155?style=for-the-badge&logoColor=white)
![Unitree Go2](https://img.shields.io/badge/Unitree_Go2-111827?style=for-the-badge&logoColor=white)
![Cobot Magic](https://img.shields.io/badge/Cobot_Magic_Dual--Arm-374151?style=for-the-badge&logoColor=white)

### 3D Vision, Learning & Agents
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![SE(3) & 3D Vision](https://img.shields.io/badge/SE(3)_%26_Affordance_Vision-2563EB?style=for-the-badge&logoColor=white)
![VGGT & DINOv2](https://img.shields.io/badge/VGGT_%2F_DINOv2-0284C7?style=for-the-badge&logoColor=white)
![OpenSpiel](https://img.shields.io/badge/OpenSpiel_%2F_CFR-4F46E5?style=for-the-badge&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![HDF5](https://img.shields.io/badge/HDF5-003B57?style=for-the-badge&logoColor=white)

### CAD, Compute & Embedded Systems
![CUDA & ROCm](https://img.shields.io/badge/CUDA_%2F_AMD_ROCm-15803D?style=for-the-badge&logo=nvidia&logoColor=white)
![Slurm](https://img.shields.io/badge/Slurm_HPC-0369A1?style=for-the-badge&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-E87D0D?style=for-the-badge&logo=blender&logoColor=white)
![SolidWorks](https://img.shields.io/badge/SolidWorks_%2F_FreeCAD-B91C1C?style=for-the-badge&logoColor=white)
![STM32 / ARM](https://img.shields.io/badge/STM32_%2F_ARM-03234B?style=for-the-badge&logo=arm&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

---

## 🎸 Guitar & Sound

Band guitarist with live stage experience — drawn to Texas blues phrasing and 70s progressive rock architecture, especially **Stevie Ray Vaughan**, **Pink Floyd** (*The Dark Side of the Moon*), and **King Crimson**.

![Electric Guitar](https://img.shields.io/badge/Electric_Guitar-18181B?style=for-the-badge&logoColor=white)
![Blues Rock](https://img.shields.io/badge/Blues_Rock_%C2%B7_SRV-92400E?style=for-the-badge&logoColor=white)
![Progressive Rock](https://img.shields.io/badge/Prog_Rock_%C2%B7_Pink_Floyd_%2F_King_Crimson-581C87?style=for-the-badge&logoColor=white)

---

## 🚗 Why `AlexDrives` · Sci-Fi & Imperfect Information

Grew up buying car magazines from neighborhood newsstands and memorizing drivetrain specs — a lifelong fascination with mechanical machines that eventually steered from engines and autonomous driving into embodied robots. Off the lab bench: Philip K. Dick & classic sci-fi cinema (*Blade Runner*, *2001: A Space Odyssey*) and decision-making under imperfect information (Texas Hold'em CFR solvers, FromSoftware worlds, *Civilization*).

---

## 📫 Contact & Email Routing

| Channel | Email | When to Use | Portfolio Route |
| --- | --- | --- | --- |
| **Academic & Primary** *(SJTU)* | [`whichAlex@sjtu.edu.cn`](mailto:whichAlex@sjtu.edu.cn) | **2027 Fall PhD / graduate admissions**, faculty outreach & academic research discussions | [`#contact/academic ↗`](https://portfolio-rouge-three-eznvbawdug.vercel.app/#contact/academic) |
| **R&D Work** *(ABB Robotics)* | [`junhao.liu@cn.abb.com`](mailto:junhao.liu@cn.abb.com) | **Real2Sim pipelines**, **Port–Mate** environment reasoning & industrial robotics R&D collaboration | [`#contact/work ↗`](https://portfolio-rouge-three-eznvbawdug.vercel.app/#contact/work) |
| **Personal & Open-Source** *(Gmail)* | [`alex20160117@gmail.com`](mailto:alex20160117@gmail.com) | Long-term personal inbox (persists beyond graduation), **GitHub open-source** issues & general correspondence | [`#contact/personal ↗`](https://portfolio-rouge-three-eznvbawdug.vercel.app/#contact/personal) |
