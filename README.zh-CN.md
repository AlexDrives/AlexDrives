<h1 align="center">你好，我是刘俊豪 · Junhao (Alex) Liu 👋</h1>

<h3 align="center">具身智能 · Real2Sim 与物理世界表征 · VLA · 机器人学习</h3>

<p align="center">
  <a href="README.md">English</a> | <strong>简体中文</strong> | <a href="README.zh-TW.md">繁體中文</a>
</p>

<p align="center">
  <a href="https://portfolio-rouge-three-eznvbawdug.vercel.app/"><img src="https://img.shields.io/badge/个人主页-junhao.liu-111111?style=for-the-badge&logo=vercel&logoColor=white" alt="个人主页" /></a>
  <a href="mailto:whichAlex@sjtu.edu.cn"><img src="https://img.shields.io/badge/邮箱-whichAlex%40sjtu.edu.cn-2B2B2B?style=for-the-badge&logo=gmail&logoColor=white" alt="邮箱" /></a>
  <a href="https://portfolio-rouge-three-eznvbawdug.vercel.app/Junhao_Liu_CV_ZH.pdf"><img src="https://img.shields.io/badge/中文简历-PDF-444444?style=for-the-badge&logo=readthedocs&logoColor=white" alt="中文简历 PDF" /></a>
  <a href="https://alexdrives.github.io/literally-me/"><img src="https://img.shields.io/badge/彩蛋主页-literally--me-0E7490?style=for-the-badge&logo=githubpages&logoColor=white" alt="literally-me 彩蛋主页" /></a>
</p>

---

### 关于我

🎓 **上海交通大学 · 智能感知工程专业** 本科在读（自动化与感知学院，2027 届 · 大三专业核心均分 `89.5/100`，《智能感知系统设计与实践》`100/100` 全班 `1/38`）  
🔬 **ABB Robotics · 环境推理研发实习生** — 构建 **Real2Sim** 资产与场景生成流程、受 CAD 装配启发的 **Port–Mate** 场景表征，以及融合几何求解与 **Critic** 物理反馈的 **LLM/VLM** 智能体*（持续研发与论文冲刺中）*  
🤖 曾任 **协创数据技术（ShareTronic） · 机器人算法实习生** — 负责 `NVIDIA Isaac Lab / Sim` 中 **宇树 Go2** 四足机器人强化学习视觉导航（`NavRL`）、`ROS2` 实机部署排障与 `VGGT` 第一视角人形导航数据预研  
🧭 **核心关注**：如何将**显式三维几何/物理约束**与**可扩展机器人学习**连接起来——打通可验证的 Real2Sim 仿真数据引擎与真机 **VLA 后训练及 System-2/1 协同执行**  
📬 正在寻找 **2027 秋季博士（PhD）/ 研究型深造与科研合作机会**（具身智能、机器人学习、Real2Sim2Real、世界模型）  

---

## 代表性研究与系统实践

- 🏆 **[蚂蚁灵波具身大模型挑战赛（`LingBot-VLA 2.0 6B`）](https://github.com/AlexDrives/lingbot-competiton-fbfyfbf)** — 发起组建五人本科生团队 `fbfyfbf`。初赛在 RoboTwin 2.0 五十项双臂仿真任务中位列 **第 6 / 1,855 队**（官方复测 Clean `82.22%` / Randomized `57.26%`；定位统计量分位数偏移缺陷，设计保相傅里叶频域增强与严格配对符号检验评测）。**48 小时松灵 Cobot Magic 双臂真机决赛获优胜奖**：主导现场遥操与 `200 Hz` 零跳变 DAgger 接管数采管线（`646` 条高质量示范），参与不停机流式训练与 16 GB 显卡上的 **Training-time / 异步实时动作分块（RTC）** 推理，以及基于 DeepSeek 的 **System-2 长程清扫子任务调度 Harness** + `20.5 万`参数腕部抓取检测 CNN（留出集准确率 `99.8%`）与第三轮数据漂移复盘。
- 🧩 **[环境推理与 Real2Sim 场景构建 @ ABB Robotics](https://portfolio-rouge-three-eznvbawdug.vercel.app/#experience/abb)** *（持续研发与论文冲刺阶段，内部技术细节暂不公开）* — 研发自动化 **Real2Sim** 资产与场景生成流程、受机械 CAD 装配启发的 **Port–Mate** 功能场景表征，以及结合几何求解与物理 **Critic** 迭代反馈的 **LLM/VLM** 智能体，并探索 Agent 辅助的仿真测试框架（Simulation Harness）。
- 🐕 **[四足强化学习视觉导航与 Sim2Real 排障 @ ShareTronic](https://portfolio-rouge-three-eznvbawdug.vercel.app/#experience/sharetronic)** — 将无人机 `NavRL` 框架跨本体迁移适配至 `NVIDIA Isaac Lab` 中的 12 自由度 **Unitree Go2** 四足机器狗，通过步态奖励塑形与延迟/噪声域随机化抑制侧身行走；在机载 `ROS2` 外场联调中定位移动目标局部占据栅格更新延迟根因，并预研基于 `VGGT + DINO` 的第一视角人类行走三维轨迹提取。
- 🧬 **[RNA-GCP-VQVAE](https://github.com/AlexDrives/RNA-GCP-VQVAE)** — 基于 $SE(3)$ 等变几何深度学习将蛋白质 `GCP-VQVAE` 扩展至 **RNA 三维主链离散表征与重建**：搭建 `RNAsolo / cd-hit-est (c80) → HDF5` 同源划分管线、6 二面角与局部刚体特征，以及轨迹级 **FAPE** 监督的 **AlphaFold2 风格 IPA 结构解码器**（坐标 MAE `1.08 Å` · TM-score `0.79`）。
- 🎲 **[机械臂自主骰子感知与高速堆叠系统](https://github.com/AlexDrives/Dice-detection-and-auto-stacking-with-OpenMV-and-OpenCV)** — 独立打通镜头畸变校正、单帧 27 枚高密骰子分割识别、450+ 点对单应性+二次残差误差补偿（平均误差 `0.740 mm`）与四自由度吸盘臂闭环控制（**26 秒连叠 6 枚 · 全班第 1 / 38**） · ♠️ **[Kuhn Poker：自博弈 RL vs. CFR](https://github.com/AlexDrives/kuhn_poker-exp)** — 在 PyTorch 中诊断朴素自博弈 REINFORCE 的策略振荡机理，并与 OpenSpiel `CFR / CFR+` 的可剥削度收敛行为做定量对照。

---

## 技术栈

### 编程语言
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-283593?style=for-the-badge&logo=c&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-B8450F?style=for-the-badge&logoColor=white)

### 具身智能、物理仿真与机器人
![NVIDIA Isaac Sim](https://img.shields.io/badge/NVIDIA_Isaac_Sim_%2F_Lab-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![OmniGibson](https://img.shields.io/badge/OmniGibson-1F2937?style=for-the-badge&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![VLA](https://img.shields.io/badge/VLA_Post--Training_%26_RTC-D97706?style=for-the-badge&logoColor=white)
![Real2Sim](https://img.shields.io/badge/Real2Sim_%26_OpenUSD-0F766E?style=for-the-badge&logoColor=white)
![RoboTwin](https://img.shields.io/badge/RoboTwin_2.0-334155?style=for-the-badge&logoColor=white)
![Unitree Go2](https://img.shields.io/badge/Unitree_Go2-111827?style=for-the-badge&logoColor=white)
![Cobot Magic](https://img.shields.io/badge/Cobot_Magic_Dual--Arm-374151?style=for-the-badge&logoColor=white)

### 三维视觉、深度学习与智能体
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![SE(3) & 3D Vision](https://img.shields.io/badge/SE(3)_%26_Affordance_Vision-2563EB?style=for-the-badge&logoColor=white)
![VGGT & DINOv2](https://img.shields.io/badge/VGGT_%2F_DINOv2-0284C7?style=for-the-badge&logoColor=white)
![OpenSpiel](https://img.shields.io/badge/OpenSpiel_%2F_CFR-4F46E5?style=for-the-badge&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![HDF5](https://img.shields.io/badge/HDF5-003B57?style=for-the-badge&logoColor=white)

### 建模、异构算力与硬件工作流
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

## 🏀 篮球、硬件黑客松与吉他

- **硬件黑客松**：最近很上头在极限时间里把真机搭起来，正在筹备下一场硬件黑客松。
- **篮球**：平时喜欢打球，**Cade Cunningham** 球迷。
- **吉他与音乐**：平时弹电吉他，常听布鲁斯和前卫摇滚，尤其喜欢 **Stevie Ray Vaughan**、**Pink Floyd** 和 **King Crimson**。

![Hardware Hackathons](https://img.shields.io/badge/Hardware_Hackathons-111827?style=for-the-badge&logoColor=white)
![Cade Cunningham](https://img.shields.io/badge/Basketball_%C2%B7_Cade_Cunningham-1D4ED8?style=for-the-badge&logoColor=white)
![Electric Guitar](https://img.shields.io/badge/Guitar_%C2%B7_SRV_%2F_Pink_Floyd_%2F_King_Crimson-92400E?style=for-the-badge&logoColor=white)

---

## 🚗 车、科幻与游戏

从小喜欢车，这也是 `AlexDrives` 这个名字的由来。闲暇时喜欢看菲利普·迪克的小说和老科幻片（《银翼杀手》《2001 太空漫游》），常玩魂系游戏、《文明》和德州扑克。

<details>
<summary>🕹️ <code>&lt;signal&gt;</code> · 隐藏彩蛋（点击展开）</summary>

```text
> SYS.UPDATING _
> free the birds!!!  [R:3/3]  [G:3/3]  [B:3/3]
> "tears in rain" — Detroit Pistons #2 · 48h real-robot bench · guitar on standby
```

欢迎来我的交互式 ASCII & Three.js 彩蛋小站 **[literally-me](https://alexdrives.github.io/literally-me/)**（[源码仓库](https://github.com/AlexDrives/literally-me)）—— 放飞小鸟、集齐页面里藏着的 RGB 锁，解锁 `<signal>`。

</details>
