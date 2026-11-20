<h1 align="center">你好，我是劉俊豪 · Junhao (Alex) Liu 👋</h1>

<h3 align="center">具身智能 · Real2Sim 與物理世界表徵 · VLA · 機器人學習</h3>

<p align="center">
  <a href="README.md">English</a> | <a href="README.zh-CN.md">简体中文</a> | <strong>繁體中文</strong>
</p>

<p align="center">
  <a href="https://portfolio-rouge-three-eznvbawdug.vercel.app/"><img src="https://img.shields.io/badge/個人主頁-junhao.liu-111111?style=for-the-badge&logo=vercel&logoColor=white" alt="個人主頁" /></a>
  <a href="mailto:whichAlex@sjtu.edu.cn"><img src="https://img.shields.io/badge/郵箱-whichAlex%40sjtu.edu.cn-2B2B2B?style=for-the-badge&logo=gmail&logoColor=white" alt="郵箱" /></a>
  <a href="https://portfolio-rouge-three-eznvbawdug.vercel.app/Junhao_Liu_CV_ZH.pdf"><img src="https://img.shields.io/badge/中文簡歷-PDF-444444?style=for-the-badge&logo=readthedocs&logoColor=white" alt="中文簡歷 PDF" /></a>
</p>

---

### 關於我

🎓 **上海交通大學 · 智能感知工程專業** 本科在讀（自動化與感知學院，2027 屆 · 大三專業核心均分 `89.5/100`，《智能感知系統設計與實踐》`100/100` 全班 `1/38`）  
🔬 **ABB Robotics · 環境推理研發實習生** — 構建 **Port-Ready Real2Sim** 資產管線（單目照片 + 自然語言 → `Blender` 參數化建模與原生端口同參同源生成 → `OmniGibson` OpenUSD）、受機械 CAD 裝配啟發的 **Port–Mate** $SE(3)$ 場景表徵，以及幾何求解器與物理 **Critic** 閉環的 `LangGraph` 仿真智能體  
🤖 曾任 **協創數據技術（ShareTronic） · 機器人演算法實習生** — 負責 `NVIDIA Isaac Lab / Sim` 中 **宇樹 Go2** 四足機器人強化學習視覺導航（`NavRL`）、`ROS2` 實機部署排障與 `VGGT` 第一視角人形導航數據預研  
🧭 **核心關注**：如何將**顯式三維幾何/物理約束**與**可擴展機器人學習**連接起來——打通可驗證的 Real2Sim 仿真數據引擎與真機 **VLA 後訓練及 System-2/1 協同執行**  
📬 正在尋找 **2027 秋季博士（PhD）/ 研究型深造與科研合作機會**（具身智能、機器人學習、Real2Sim2Real、世界模型）  

---

## 代表性研究與系統實踐

- 🏆 **[螞蟻靈波具身大模型挑戰賽（`LingBot-VLA 2.0 6B`）](https://github.com/AlexDrives/lingbot-competiton-fbfyfbf)** — 發起組建五人本科生團隊 `fbfyfbf`。初賽在 RoboTwin 2.0 五十項雙臂仿真任務中位列 **第 6 / 1,855 隊**（官方複測 Clean `82.22%` / Randomized `57.26%`；定位統計量分位數偏移缺陷，設計保相傅立葉頻域增強與嚴格配對符號檢驗評測）。**48 小時松靈 Cobot Magic 雙臂真機決賽獲優勝獎**：主導現場遙操與 `200 Hz` 零跳變 DAgger 接管數採管線（`646` 條高質量示範），參與不停機流式訓練與 16 GB 顯卡上的 **Training-time / 異步實時動作分塊（RTC）** 推理，以及基於 DeepSeek 的 **System-2 長程清掃子任務調度 Harness** + `20.5 萬`參數腕部抓取檢測 CNN（留出集準確率 `99.8%`）與第三輪數據漂移復盤。
- 🧩 **[Port-Ready Real2Sim 與 Port–Mate 場景終態推理（`AssemWorld`）](https://portfolio-rouge-three-eznvbawdug.vercel.app/#experience/abb)** — 打通端到端 **Port-Ready Real2Sim** 管線（單目參考照片 + 自然語言 → VLM 與 `Blender` `port_kit` 同參同源生成幾何與原生端口 + 四視圖視覺自檢 → 端口引導解析凸分解防止盲孔/容腔被封堵 → 視覺/碰撞雙幾何校驗導出 `OmniGibson` OpenUSD），並與 `Port–Mate` $SE(3)$ 裝配約束求解（$T_i = T_b L_b M(\theta) L_i^{-1}$，$S_{\text{op}} \xrightarrow{\text{OmniGibson}} S_{\text{evo}}$、`89/89` 物理驗收）及獨立幾何 Oracle 支撐面發現（精度 `0.979`）閉環打通。
- 🐕 **[四足強化學習視覺導航與 Sim2Real 排障 @ ShareTronic](https://portfolio-rouge-three-eznvbawdug.vercel.app/#experience/sharetronic)** — 將無人機 `NavRL` 框架跨本體遷移適配至 `NVIDIA Isaac Lab` 中的 12 自由度 **Unitree Go2** 四足機器狗，通過步態獎勵塑形與延遲/噪聲域隨機化抑制側身行走；在機載 `ROS2` 外場聯調中定位移動目標局部佔據柵格更新延遲根因，並預研基於 `VGGT + DINO` 的第一視角人類行走三維軌跡提取。
- 🧬 **[RNA-GCP-VQVAE](https://github.com/AlexDrives/RNA-GCP-VQVAE)** — 基於 $SE(3)$ 等變幾何深度學習將蛋白質 `GCP-VQVAE` 擴展至 **RNA 三維主鏈離散表徵與重建**：搭建 `RNAsolo / cd-hit-est (c80) → HDF5` 同源劃分管線、6 二面角與局部剛體特徵，以及軌跡級 **FAPE** 監督的 **AlphaFold2 風格 IPA 結構解碼器**（座標 MAE `1.08 Å` · TM-score `0.79`）。
- 🎲 **[機械臂自主骰子感知與高速堆疊系統](https://github.com/AlexDrives/Dice-detection-and-auto-stacking-with-OpenMV-and-OpenCV)** — 獨立打通鏡頭畸變校正、單幀 27 枚高密骰子分割識別、450+ 點對單應性+二次殘差誤差補償（平均誤差 `0.740 mm`）與四自由度吸盤臂閉環控制（**26 秒連疊 6 枚 · 全班第 1 / 38**） · ♠️ **[Kuhn Poker：自博弈 RL vs. CFR](https://github.com/AlexDrives/kuhn_poker-exp)** — 在 PyTorch 中診斷樸素自博弈 REINFORCE 的策略振盪機理，並與 OpenSpiel `CFR / CFR+` 的可剝削度收斂行為做定量對照。

---

## 技術棧

### 編程語言
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-283593?style=for-the-badge&logo=c&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-B8450F?style=for-the-badge&logoColor=white)

### 具身智能、物理仿真與機器人
![NVIDIA Isaac Sim](https://img.shields.io/badge/NVIDIA_Isaac_Sim_%2F_Lab-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![OmniGibson](https://img.shields.io/badge/OmniGibson-1F2937?style=for-the-badge&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![VLA](https://img.shields.io/badge/VLA_Post--Training_%26_RTC-D97706?style=for-the-badge&logoColor=white)
![Real2Sim](https://img.shields.io/badge/Real2Sim_%26_OpenUSD-0F766E?style=for-the-badge&logoColor=white)
![RoboTwin](https://img.shields.io/badge/RoboTwin_2.0-334155?style=for-the-badge&logoColor=white)
![Unitree Go2](https://img.shields.io/badge/Unitree_Go2-111827?style=for-the-badge&logoColor=white)
![Cobot Magic](https://img.shields.io/badge/Cobot_Magic_Dual--Arm-374151?style=for-the-badge&logoColor=white)

### 三維視覺、深度學習與智能體
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![SE(3) & 3D Vision](https://img.shields.io/badge/SE(3)_%26_Affordance_Vision-2563EB?style=for-the-badge&logoColor=white)
![VGGT & DINOv2](https://img.shields.io/badge/VGGT_%2F_DINOv2-0284C7?style=for-the-badge&logoColor=white)
![OpenSpiel](https://img.shields.io/badge/OpenSpiel_%2F_CFR-4F46E5?style=for-the-badge&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![HDF5](https://img.shields.io/badge/HDF5-003B57?style=for-the-badge&logoColor=white)

### 建模、異構算力與硬體工作流
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

## 🎸 音樂與吉他

平時喜歡彈電吉他，常聽藍調（Blues）和前衛搖滾，尤其喜歡 **Stevie Ray Vaughan**、**Pink Floyd** 和 **King Crimson**。

![Electric Guitar](https://img.shields.io/badge/Electric_Guitar-18181B?style=for-the-badge&logoColor=white)
![SRV](https://img.shields.io/badge/Stevie_Ray_Vaughan-92400E?style=for-the-badge&logoColor=white)
![Pink Floyd & King Crimson](https://img.shields.io/badge/Pink_Floyd_%C2%B7_King_Crimson-581C87?style=for-the-badge&logoColor=white)

---

## 🚗 車、科幻與遊戲

從小喜歡車，這也是 `AlexDrives` 這個名字的由來。閒暇時喜歡看菲利普·迪克的小說和經典科幻電影（《銀翼殺手》《2001 太空漫遊》），常玩魂系遊戲、《文明》和德州撲克。
