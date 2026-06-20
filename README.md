# Wang Kai / galaxywk223

**Anhui University of Technology**

公开项目主要围绕机器学习实验、控制优化原型、学习系统和开发工具展开。仓库内容既包括可复现实验、竞赛方案和研究型基准，也包括面向本地使用的完整应用系统。

Public repositories here focus on machine learning experiments, control and optimization prototypes, learning systems, and developer tools.

[GitHub Profile](https://github.com/galaxywk223)

## Research and Experiments / 研究与实验

### [kaggle-nvidia-nemotron-model-reasoning-challenge](https://github.com/galaxywk223/kaggle-nvidia-nemotron-model-reasoning-challenge)

NVIDIA Nemotron Model Reasoning Challenge 的 Kaggle 银牌方案，围绕 `Nemotron-3-Nano-30B` 的 rank-32 LoRA SFT、CoT 样本构造、适配器实验和最终 Private LB #167 结果展开。

A silver-medal Kaggle reasoning solution built around LoRA fine-tuning, adapter experiments, and submission automation.

### [robust-battery-mpc](https://github.com/galaxywk223/robust-battery-mpc)

退化感知鲁棒 MPC 电池套利实验，围绕电价预测下的充放电决策、退化建模和风险收益权衡展开。项目保留了 MILP 调度实现、bootstrap 评估和主要结果表。

Degradation-aware robust MPC for battery arbitrage under electricity price forecasts.

### [contract-aware-rh-control-benchmark](https://github.com/galaxywk223/contract-aware-rh-control-benchmark)

面向可部署滚动时域控制评估的契约感知基准。项目比较 battery arbitrage、BOPTEST building control 和 inventory control 等任务下，评价契约变化如何影响控制器排序和稳定性判断。

A contract-aware benchmark for deployable receding-horizon control evaluation.

### [ordered-shift-policy-selection](https://github.com/galaxywk223/ordered-shift-policy-selection)

面向有序分布偏移的策略选择实验，重点放在可解释阈值和区间选择器。项目关注部署偏移下如何从候选策略中做更稳健的选择。

Interpretable threshold and interval selectors for ordered-shift policy selection.

### [DeepLearning-Study-and-Experiments](https://github.com/galaxywk223/DeepLearning-Study-and-Experiments)

深度学习中文学习笔记与 PyTorch 实验仓库，覆盖 MNIST、CIFAR-10 ResNet、字符级 Transformer、子词级 GPT，以及基于 `Qwen2.5-0.5B-Instruct` 的 LoRA/SFT 领域助教实验。

Structured deep learning notes and experiments from CNNs to small LLM fine-tuning workflows.

### [ReinforcementLearning-Study-and-Experiments](https://github.com/galaxywk223/ReinforcementLearning-Study-and-Experiments)

强化学习中文学习笔记与可复现实验仓库，覆盖动态规划、表格方法、DQN、策略梯度、PPO、SAC 与安全强化学习专题。每条实验线保留运行入口、结果图和摘要说明。

Reproducible reinforcement learning notes and experiments across classic and deep RL methods.

### [ModernControlTheory-Study-and-Experiments](https://github.com/galaxywk223/ModernControlTheory-Study-and-Experiments)

现代控制理论主干学习线与配套数值实验，覆盖状态空间、稳定性、可控可观、观测器、最优控制、采样控制与鲁棒控制。

Modern control theory notes and numerical experiments with Python and MATLAB tracks.

## Systems and Tools / 系统与工具

### [yinghuoji-desktop](https://github.com/galaxywk223/yinghuoji-desktop)

萤火集桌面端独立仓库，面向单用户、本地优先的学习记录与分析。系统使用 Vue、Tauri、Rust 和 SQLite 构建，覆盖记录、专注、统计、阶段管理和数据维护。

A local-first desktop study tracking and analytics application built with Vue, Tauri, Rust, and SQLite.

### [learning-analytics-system](https://github.com/galaxywk223/learning-analytics-system)

围绕学习记录、专注、数据分析、预测与 AI 复盘规划构建的个人学习分析系统。它和桌面端一起构成学习分析产品线的不同阶段。

A full-stack learning analytics system for study records, focus tracking, data analysis, and review planning.

### [dachuang-ms](https://github.com/galaxywk223/dachuang-ms)

基于 Django 与 Vue 的大创项目管理平台，覆盖申报、审核、立项发布、数据中心、任务中心和统计驾驶舱。仓库保留脱敏截图、测试、数据库结构和本地验证命令。

A Django and Vue project management platform for full-cycle student innovation project workflows.

## Project Index / 项目索引

### Data Science and Learning / 数据科学与学习

- [kaggle-birdclef-plus-2026](https://github.com/galaxywk223/kaggle-birdclef-plus-2026)：面向 BirdCLEF+ 2026 的 CPU 可运行生物声学物种识别流程。 / CPU-ready bioacoustic species recognition pipeline.
- [kaggle-playground-s6e4](https://github.com/galaxywk223/kaggle-playground-s6e4)：面向 Kaggle Playground S6E4 的灌溉需求表格集成流程。 / Tabular ensemble pipeline for irrigation-need classification.
- [kaggle-titanic](https://github.com/galaxywk223/kaggle-titanic)：Titanic 生存预测入门笔记本，包含 EDA 与决策树基线。 / Starter Titanic notebooks with EDA and a decision-tree baseline.

### Application Systems / 应用系统

- [library-management-system](https://github.com/galaxywk223/library-management-system)：基于 Spring Boot 3 与 Vue 3 的图书管理系统课程设计。 / Library management system with Spring Boot 3 and Vue 3.
- [attendance-system](https://github.com/galaxywk223/attendance-system)：基于 .NET 8 WPF 与 SQLite 的学员考勤管理系统。 / Attendance management desktop system with .NET 8 WPF and SQLite.
- [shopping-platform](https://github.com/galaxywk223/shopping-platform)：基于 Spring Boot 3 与 Vue 3 的在线购物系统课程设计。 / Online shopping platform with Spring Boot 3 and Vue 3.
- [todo-app](https://github.com/galaxywk223/todo-app)：支持本地持久化、主题切换和 OpenHarmony 适配的 Flutter 待办应用。 / Flutter todo application with local persistence and OpenHarmony adaptation.
- [my-learning-logger](https://github.com/galaxywk223/my-learning-logger)：萤火集早期 Flask Web 实现，面向学习记录与个人复盘。 / Early Flask implementation of the Yinghuoji study logging workflow.

### Developer Utilities / 开发工具

- [codex-plugin-unlocker](https://github.com/galaxywk223/codex-plugin-unlocker)：Windows 版 Codex Desktop 插件入口修复工具。 / Windows utility for restoring Codex Desktop plugin entry points.
- [copy-algo-problems](https://github.com/galaxywk223/copy-algo-problems)：面向 Chromium 浏览器的算法题面 Markdown 复制扩展。 / Chromium extension for copying programming problem statements as Markdown.
- [leetcode-copy-script](https://github.com/galaxywk223/leetcode-copy-script)：LeetCode 与力扣题面 Markdown 复制用户脚本。 / Tampermonkey userscript for copying LeetCode problem statements as Markdown.

### Course and Algorithm Projects / 课程与算法项目

- [chatroom](https://github.com/galaxywk223/chatroom)：基于 C++20、POSIX socket 与 pthread 的 Linux 多用户命令行聊天室。 / Linux command-line chatroom with C++20, POSIX sockets, and pthread.
- [gomoku](https://github.com/galaxywk223/gomoku)：基于 C++20 与 Qt 6 的五子棋桌面游戏课程设计。 / Gomoku desktop game with C++20 and Qt 6.
- [tank-battle](https://github.com/galaxywk223/tank-battle)：基于 C++20 与 SDL2 的坦克大战游戏课程设计。 / Tank battle game with C++20 and SDL2.
- [animated-maze](https://github.com/galaxywk223/animated-maze)：基于 C++20 与 Qt 6 的迷宫生成与寻路可视化系统。 / Maze generation and pathfinding visualization with C++20 and Qt 6.
- [big-integer-multiply](https://github.com/galaxywk223/big-integer-multiply)：基于 C++20 的大整数乘法实现，包含朴素乘法和 Karatsuba 乘法。 / Big integer multiplication with naive and Karatsuba methods.
- [c-address-book](https://github.com/galaxywk223/c-address-book)：基于 C 语言的控制台通讯录管理系统。 / Console address book management system in C.

## Repository Policy / 展示边界

- Public original source repositories form the profile project surface.
- Public forks are excluded from the project map.
- Private repositories, local paths, credentials, and real operational data are not listed.
