<h1 align="center">你好，我是刘俊豪 · Junhao (Alex) Liu 👋</h1>

<h3 align="center">具身智能 · Real2Sim 与物理世界表征 · VLA · 机器人学习</h3>

<p align="center">
  <a href="README.md">English</a> | <strong>简体中文</strong>
</p>

<p align="center">
  <a href="https://portfolio-rouge-three-eznvbawdug.vercel.app/"><img src="https://img.shields.io/badge/个人主页-junhao.liu-111111?style=for-the-badge&logo=vercel&logoColor=white" alt="个人主页" /></a>
  <a href="mailto:whichAlex@sjtu.edu.cn"><img src="https://img.shields.io/badge/邮箱-whichAlex%40sjtu.edu.cn-2B2B2B?style=for-the-badge&logo=gmail&logoColor=white" alt="邮箱" /></a>
  <a href="https://portfolio-rouge-three-eznvbawdug.vercel.app/Junhao_Liu_CV_ZH.pdf"><img src="https://img.shields.io/badge/中文简历-PDF-444444?style=for-the-badge&logo=readthedocs&logoColor=white" alt="中文简历 PDF" /></a>
</p>

---

### 关于我

🎓 **上海交通大学 · 智能感知工程专业** 本科在读（自动化与感知学院，2027 届 · 大三专业核心均分 `89.5/100`，《智能感知系统设计与实践》`100/100` 全班 `1/38`）  
🔬 **ABB Robotics · 环境推理研发实习生** — 构建 `SimFoundry` × `OmniGibson` 自动化 **Real2Sim** 资产管线、受机械 CAD 装配启发的 **Port–Mate** $SE(3)$ 场景表征，以及几何求解器与物理 **Critic** 闭环的 `LangGraph` 仿真智能体  
🤖 曾任 **协创数据技术（ShareTronic） · 机器人算法实习生** — 负责 `NVIDIA Isaac Lab / Sim` 中 **宇树 Go2** 四足机器人强化学习视觉导航（`NavRL`）、`ROS2` 实机部署排障与 `VGGT` 第一视角人形导航数据预研  
🧭 **核心关注**：如何将**显式三维几何/物理约束**与**可扩展机器人学习**连接起来——打通可验证的 Real2Sim 仿真数据引擎与真机 **VLA 后训练及 System-2/1 协同执行**  
📬 正在寻找 **2027 秋季博士（PhD）/ 研究型深造与科研合作机会**（具身智能、机器人学习、Real2Sim2Real、世界模型）  

---

## 代表性研究与系统实践

- 🏆 **[蚂蚁灵波具身大模型挑战赛（`LingBot-VLA 2.0 6B`）](https://github.com/AlexDrives/lingbot-competiton-fbfyfbf)** — 发起组建五人本科生团队 `fbfyfbf`。初赛在 RoboTwin 2.0 五十项双臂仿真任务中位列 **第 6 / 1,855 队**（官方复测 Clean `82.22%` / Randomized `57.26%`；定位统计量分位数偏移缺陷，设计保相傅里叶频域增强与严格配对符号检验评测）。**48 小时松灵 Cobot Magic 双臂真机决赛获优胜奖**：主导现场遥操与 `200 Hz` 零跳变 DAgger 接管数采管线（`646` 条高质量示范），参与不停机流式训练与 16 GB 显卡上的 **Training-time / 异步实时动作分块（RTC）** 推理，以及基于 DeepSeek 的 **System-2 长程清扫子任务调度 Harness** + `20.5 万`参数腕部抓取检测 CNN（留出集准确率 `99.8%`）与第三轮数据漂移复盘。
- 🧩 **[Real2Sim 与 Port–Mate 场景终态推理 @ ABB Robotics](https://portfolio-rouge-three-eznvbawdug.vercel.app/#experience/abb)** — 将自然语言场景构建建模为可经物理演化验收的 `Port–Mate` $SE(3)$ 装配约束求解问题（$T_i = T_b L_b M(\theta) L_i^{-1}$，$S_{\text{op}} \xrightarrow{\text{OmniGibson}} S_{\text{evo}}$），覆盖 `on / seat / insert / in / free_in / joint` 六类关系谓词、六阶段扫描 USD 物理标准化门控（`89/89` 物理验收测试通过）与独立几何 Oracle 交叉评测的自动支撑面发现（精度 `0.979`）。
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

## 🎸 吉他与摇滚

乐队吉他手，有过现场舞台演出经历——偏爱德州布鲁斯的颗粒感与七十年代前卫摇滚的结构张力，最常听 **Stevie Ray Vaughan**、**Pink Floyd**（*The Dark Side of the Moon*）与 **King Crimson**。

![Electric Guitar](https://img.shields.io/badge/Electric_Guitar-18181B?style=for-the-badge&logoColor=white)
![Blues Rock](https://img.shields.io/badge/Blues_Rock_%C2%B7_SRV-92400E?style=for-the-badge&logoColor=white)
![Progressive Rock](https://img.shields.io/badge/Prog_Rock_%C2%B7_Pink_Floyd_%2F_King_Crimson-581C87?style=for-the-badge&logoColor=white)

---

## 🚗 为什么叫 `AlexDrives` · 科幻与不完全信息博弈

小时候总守着街角红色报刊亭买汽车杂志、背各家发动机与变速箱参数；那份对机械与驾驶的着迷，后来一路从汽车与自动驾驶把我带进了具身机器人。实验室之外，偏爱菲利普·迪克与经典科幻电影（《银翼杀手》《2001 太空漫游》），以及一切关于试错与不完全信息决策的游戏（德州扑克 CFR Solver、魂系世界、《文明》）。
