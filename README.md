# 何皓廷 · Hao-Ting (Lex) Ho

東海大學電機工程學系，2027 年 5 月畢業。做機器人：狀態估計與感測器融合最深，控制從國中開始，ROS 2 與嵌入式做到實機，現在把力氣放在多機器人。每個演算法自己寫一遍、放進模擬器裡量給自己看。  
Robotics student, Tunghai University (EE, class of 2027). Deepest in state estimation and sensor fusion, control since junior high, ROS 2 and embedded down to real hardware; now working on multi-robot systems. I write the algorithms myself so I know where they break.

🔗 **[jadiouo.github.io](https://jadiouo.github.io)** — 專案總覽 / project index

## Now

- **TartanIMU Challenge**（CMU AirLab, IROS 2026 workshop）：單一模型跨 car / drone / quadruped / handheld 四種平台的 IMU 估計
- **感知劣化環境下的多機器人主動探索**（environment-active multi-robot exploration）：大學專題，寫成 letter 投 IEEE RA-L
- 一篇關於 **sensor-only 加速度計偏差估計之測量效度**的論文，投稿 IEEE Transactions on Instrumentation and Measurement（審稿中）

## Featured

| | |
|---|---|
| **[gz-drone-swarm-pursuit](https://github.com/Jadiouo/gz-drone-swarm-pursuit)** | 3D drone-swarm cooperative pursuit in Gazebo Harmonic + ROS 2 Jazzy. Free-flying microgravity dynamics, so it doubles as a ground testbed for spacecraft rendezvous & proximity operations. |
| **[boids-swarm-pursuit](https://github.com/Jadiouo/boids-swarm-pursuit)** | ROS 2 多機器人群體智慧：分散式、局部感知的 boids 合作圍捕 2× 速度的目標——群聚、追捕策略階梯、感測模型、資訊分享、自適應目標。 |
| **[pixels-to-pose](https://github.com/Jadiouo/pixels-to-pose)** | ArUco 偵測 + 6-DoF 位姿估計，合成資料、驗證優先；為 JAXA Kibo-RPC（國際太空站機器人挑戰賽）的視覺模組而做。 |
| **[scarce-actuator-arbitration](https://github.com/Jadiouo/scarce-actuator-arbitration)** | When two robots call for the one actuator that can help them, "serve the most urgent" is what everyone writes down — this checks whether it holds when urgency is private, noisy and free to claim. |
| **[linear-algebra-lab](https://github.com/Jadiouo/linear-algebra-lab)** | 從向量空間公理到 AI：八個互動專案，核心演算法全部手刻，純 Vanilla JS + Canvas，588 個單元測試。[線上版](https://jadiouo.github.io/linear-algebra-lab/) |
| **[bayesian-inference-portfolio](https://github.com/Jadiouo/bayesian-inference-portfolio)** | 一條式子 p(θ\|D) ∝ p(D\|θ)·p(θ)，五個領域、十個完整專案：把不確定性量化成可執行的決策。 |
| **[voicetype](https://github.com/Jadiouo/voicetype)** | Fcitx5 語音聽寫模組（Rust）：按住熱鍵說話、放開後文字出現在游標處，SenseVoice 全本機推論，0 VRAM。 |
| **[grid-path-planning](https://github.com/Jadiouo/grid-path-planning)** | Occupancy grid 上的 A\* 與 RRT\*（rewire 時傳播子樹成本），純 NumPy，同一張地圖上的對照與測試。 |
| **[inverted-pendulum-control](https://github.com/Jadiouo/inverted-pendulum-control)** | 倒單擺：極點配置 vs LQR 放在同一個非線性模型上比，致動器飽和下的回正範圍。 |
| **[startup-trends-rag](https://github.com/Jadiouo/startup-trends-rag)** | pgvector + 本地 embedding + 任何 LLM 的個人 RAG，帶引用的回答，蒸餾成 agent 可載入的 skill.md。 |
| **[gtd-cli](https://github.com/Jadiouo/gtd-cli)** | 終端機裡的 Getting Things Done：inbox、情境、下一步行動、每週回顧、undo。 |

## Toolbox

`ROS 2 (Jazzy)` `Gazebo` `Webots` `Python / NumPy / PyTorch` `Rust` `C++ / Arduino / ESP32` `OpenCV` `PostgreSQL + pgvector`

<sub>Traditional Chinese first, English where it helps. Everything here is MIT unless a repo says otherwise.</sub>
