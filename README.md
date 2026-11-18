<h1 align="center">Hi, I'm Junhao (Alex) Liu · 刘俊豪 👋</h1>

<h3 align="center">Embodied AI · Real2Sim & World Representations · VLA · Robot Learning</h3>

<p align="center">
  <strong>English</strong> | <a href="README.zh-CN.md">简体中文</a>
</p>

<p align="center">
  <a href="https://portfolio-rouge-three-eznvbawdug.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-junhao.liu-111111?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="mailto:whichAlex@sjtu.edu.cn"><img src="https://img.shields.io/badge/Email-whichAlex%40sjtu.edu.cn-2B2B2B?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://portfolio-rouge-three-eznvbawdug.vercel.app/Junhao_Liu_CV.pdf"><img src="https://img.shields.io/badge/CV-PDF-444444?style=for-the-badge&logo=readthedocs&logoColor=white" alt="CV PDF" /></a>
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

## 🎸 Music & Guitar

Play electric guitar in my spare time, and listen to a lot of blues and progressive rock — especially **Stevie Ray Vaughan**, **Pink Floyd**, and **King Crimson**.

![Electric Guitar](https://img.shields.io/badge/Electric_Guitar-18181B?style=for-the-badge&logoColor=white)
![SRV](https://img.shields.io/badge/Stevie_Ray_Vaughan-92400E?style=for-the-badge&logoColor=white)
![Pink Floyd & King Crimson](https://img.shields.io/badge/Pink_Floyd_%C2%B7_King_Crimson-581C87?style=for-the-badge&logoColor=white)

---

## 🚗 Cars, Sci-Fi & Games

Into cars since childhood (where the handle `AlexDrives` comes from). Outside work, I enjoy sci-fi books and films (*Do Androids Dream of Electric Sheep?*, *Blade Runner*, *2001: A Space Odyssey*) and games like *Dark Souls*, *Civilization*, and Texas Hold'em.
