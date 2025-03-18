---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div id="about-me"></div>

# 👨‍🎓 个人简介

我是[北京理工大学](https://www.bit.edu.cn)自动化专业的二年级硕士研究生，作为**自主智能无人系统国家重点实验室**的一员，专注于无人机/无人车路径规划及其支撑技术，如SLAM、运动控制及多机器人协作。我于2023年获得*北京理工大学(BIT)*自动化专业的工学学士学位。

我的研究兴趣包括**无人机/无人车路径规划与运动控制**等，并在这些方面具有丰富的动手能力与项目经验。我在国际会议上发表过多篇论文，包括IEEE ICCA以及IEEE RCAR。

<div id="skills"></div>

# 💪 素质能力

**专业背景**：研究方向为**无人系统自主导航与控制**，包括**无人机/无人车**路径规划与控制、未知环境探索等。

**开发经验**：

  - 无人机/无人车软硬件开发经验丰富，熟练使用ROS平台、PX4飞控、Gazebo仿真；
  - 熟悉Linux系统基本操作以及Git、CMake、VS Code、NeoVim等工具；
  - 熟悉Hybrid A\*、D\*等路径规划算法，熟悉PID、MPC等控制算法；
  - 了解OSQP、CasAdi等数值优化库。

**编程语言**：熟练使用C/C++、Python，了解C++ Boost/Eigen/PCL库、Python Pytorch/Numpy等框架，熟悉MATLAB基础语法。

**英语水平**：四六级已通过，具有良好的英语写作、交流与文献阅读能力。

**其他**：具有硬件软件动手调试能力，了解SolidWorks基础使用。

<div id="education"></div>

# 📖 教育经历

## 北京理工大学/徐特立英才班（北理工拔尖人才培养特区）

`2019.9-2023.6 | 工学学士学位 | 自动化方向`

  - 学分绩：85.0/100，多次获得**一等**学业奖学金

## 北京理工大学/控制工程（模式识别与智能系统方向）

`2023.6-至今 | 工学硕士学位 | 保研`

  - 学分绩：86.1/100，多次获得**一等**学业奖学金
  - 获得中国机器人及人工智能大赛**一等奖**、“华为杯”中国研究生数学建模竞赛**三等奖**

<div id="projects"></div>

# 📁 项目比赛

## 空地异构平台协同的室内导航与侦测（**国家重点研发计划**）

`🕒2021.10-2025.3 | 开发（无人机决策规划）`

**技术体系**：多机协同SLAM · Kinodynamic A* · LBFGS优化 · ESDF地图构建

**项目描述**：面向自然灾害中受损建筑物内的复杂未知室内环境，使用多无人机平台，根据搭载的感知设备扫描受灾环境信息实时建图，同时进行完全自主决策，探索目标场景并自主规划飞行轨迹。

**个人工作**

  1. 负责设计规划子模块的状态机，实现无人机起飞、探索、规划、返航全流程自主状态切换；
  2. 在完全未知环境中，使用无人机搭载的雷达设备获取点云信息，运用Kinodynamic A*算法获取里程计到未探索区域目标的初始无碰撞路径；
  3. 构建局部ESDF地图，建立避障轨迹的非线性优化模型，应用LBFGS算法优化获得一条平滑、无障碍、满足动力学约束的路径。

**项目成果**：在探索复杂未知室内环境过程中，项目实现多机协同室内定位精度误差不超过8.5cm，所构建的室内三维地图重建精度误差不超过4.6cm，实现了4架无人平台协同执行航迹规划与侦测任务。

---

## “华为杯”中国研究生数学建模竞赛（**国家级比赛**）

`🕒2023.9 | 🏆全国三等奖 | 算法架构`

**技术栈**：Pytorch · 模糊控制系统 · 极差修正算法

**比赛描述**：针对大规模跨学科创新竞赛因评审标准模糊化、专家主观倾向差异显著（评分极差达35%以上）导致的公正性争议，赛事亟需构建科学评审体系，实现评审客观性与公信力的结构化提升。

**个人工作**

  1. 使用Pytorch构建自定义神经网络，从原始专家打分学习评审模式，利用该模型重新打分，标准差降低15.87%，提升了打分有效性；
  2. 结合模糊系统和神经网络设计程序化极差调整策略，复议分数极差对比参考分数极差得到显著降低，降低比率71.43%，同时调整后均值分数标准差与原始数据插值2.73，验证该策略能够在稳定评价同时调整极差范围。

**比赛成果**：提出了一整套完整的优化评审方案，可以有效地辅助大规模创新类竞赛更加公平地评审。研究结果经过赛事组委会评定，最终获得三等奖。

---

## 中国机器人及人工智能大赛（无人协同系统）（**国家级比赛**）

`🕒2024.3-2024.8 | 🏆全国一等奖 | 无人机系统决策规划`

**技术亮点**：Minimum Snap轨迹优化 · OpenCV视觉伺服 · 树莓派嵌入式开发

**比赛描述**：模拟地下仓库中无人车+无人机的空地一体化常规巡检。无人机起飞后，根据任务需求，自主规划飞行轨迹，避开障碍物并穿过门框，识别移动中的无人车顶二维码后降落到指定区域。

**个人工作**

  1. 运用Minimum Snap方法，将无人机运行轨迹建模为多项式函数表达，引入松弛变量最小化轨迹时间，获得能量消耗低、运行时间短的初始路径；
  2. 使用C++ OpenCV读取无人车搭载相机的RGB图像，识别地面黑色轨迹并编写无人车巡线逻辑，部署到树莓派平台控制无人车，实现上电自动识别轨迹循迹运行；

**比赛成果**：无人机正常起飞后，快速躲避障碍物，穿越门窗，飞行至无人车上方识别二维码并在控制台输出对应的内容，前往指定区域降落。在9米*5米的场地中，从起飞到降落最终用时37秒，获得大赛一等奖。

---

## 无人机群协同控制研究技术

`🕒2022.7-至今 | 硬件工程师`

**项目描述**：构建支持任意数量智能体、可高效协同探索的无人集群，进行未知环境态势评估。

**个人工作**

  1. 从零构建小型无人机：从硬件选型、连接件设计，到飞控配置、软硬件联调；
  2. 部署了多种主流无人机建图、探索、跟踪与规划算法，负责测试对比小型无人机的性能。

**项目成果**：构建了多种类型的小型自主无人机，分别基于深度相机与激光雷达，并且嵌入相应的视觉与激光里程计，具有不弱于各厂家所制作的科研无人机性能水平。

<div id="papers"></div>

# 📝 论文发表

<div class="paper-box">
  <div class="paper-box-image">
    <div class="badge">ICCA 2025</div>
    <img src="images/icca-paper.png" alt="sym" width="100%">
  </div>
  <div class="paper-box-text">
    <!-- <a href="https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf">
      <strong>Autonomous UAV Path Planning in Dynamic Environments: A Hybrid Framework of Trajectory Prediction and Priority-Aware DWA</strong>
    </a> -->
    <strong>Autonomous UAV Path Planning in Dynamic Environments: A Hybrid Framework of Trajectory Prediction and Priority-Aware DWA</strong>
    <p><strong><em>Fengrui Ran</em></strong>, Chengpu Yu, Erpei Xu, Yunji Feng</p>
    <!-- <a href="https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC">
      <strong>工作创新</strong>
    </a> -->
    <strong>论文创新</strong>
    <ul>
      <li>通过动态障碍物位置与时间戳构建二次规划（QP）问题实现对其未来行动轨迹的预测，同时结合随时间膨胀的不确定信息描述未来时间下障碍物形状；</li>
      <li>扩展长期动态窗口（LT-DWA）方法，采取多叉树结构存储搜索信息，同时引入节点优先级概念加快搜索，融合不确定信息的动态障碍物碰撞与未来时刻碰撞代价以降低可能的局部最优概率；</li>
      <li>应用模型预测（MPC）方法构建轨迹优化问题，过程中融入无人机控制变量，实现了轨迹的快速优化与角速度控制量获取，运行速度可达100Hz，在仿真和实机环境进行了整套系统的验证。 </li>
    </ul>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div class="badge">RCAR 2025</div>
    <img src="images/rcar-paper.png" alt="sym" width="100%">
  </div>
  <div class="paper-box-text">
    <!-- <a href="https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf">
      <strong>ExploreGS: a vision-based low overhead framework for 3D scene reconstruction</strong>
    </a> -->
    <strong>ExploreGS: a vision-based low overhead framework for 3D scene reconstruction</strong>
    <p>Yunji Feng, Chengpu Yu, <strong><em>Fengrui Ran</em></strong>, Zhi Yang, Yinni Liu</p>
    <!-- <a href="https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC">
      <strong>参与工作</strong>
    </a> -->
    <strong>论文创新</strong>
    <ul>
      <li>提出了一种基于快速视觉模型的数据采集方法，可以有效地探索未知环境并生成点云；</li>
      <li>基于词袋模型设计了一种对选方案，可以减少84-95%的冗余数据；</li>
      <li>在仿真与实机环境验证了自主重建框架的有效性，同时可以实现无人机上的实时推理。</li>
    </ul>
  </div>
</div>

<div id="awards"></div>

# 🏅 荣誉奖项
- *2024* 中国机器人及人工智能大赛**一等奖**（**国家级**）
- *2024* 中国研究生数学建模竞赛**三等奖**（**国家级**）
- *2023* 全国大学生课外学术科技作品竞赛**一等奖**（院校级）
- *2023* “互联网+”大学生创新创业大赛**铜奖**（院校级）
