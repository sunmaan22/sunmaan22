<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:14c7ae,100:0a0c0f&height=210&section=header&text=sunmaan22&fontSize=54&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Perception%20%C2%B7%20Planning%20%C2%B7%20Control&descAlignY=54&descSize=18" />

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&size=20&pause=1200&color=14C7AE&center=true&vCenter=true&width=560&lines=%EC%84%BC%EC%84%9C%EB%A5%BC%20%EC%9D%BD%EA%B3%A0%2C%20%ED%8C%90%EB%8B%A8%EC%9D%84%20%EC%84%A4%EA%B3%84%ED%95%98%EA%B3%A0%2C%20%EC%B0%A8%EC%B2%B4%EB%A5%BC%20%EC%9B%80%EC%A7%81%EC%9D%B8%EB%8B%A4.;Perception%20%C2%B7%20Planning%20%C2%B7%20Control;Xycar%20%C2%B7%20MORAI%20%C2%B7%20Raspberry%20Pi%20%C2%B7%20STM32" alt="Typing SVG" />

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-sunmaan22.github.io-14c7ae?style=for-the-badge)](https://sunmaan22.github.io)
[![Email](https://img.shields.io/badge/Email-sunmaan22%40gmail.com-14c7ae?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sunmaan22@gmail.com)

자율주행과 로보틱스의 **인지 · 판단 · 제어** 전 계층을 하드웨어부터 소프트웨어까지 직접 구현합니다.<br/>
Xycar 스케일카부터 안내 보조 로봇, 엣지 AI 기반 산업 안전 모니터링까지 — [포트폴리오에서 프로젝트 전체 보기 →](https://sunmaan22.github.io)

</div>

---

### 🛠 Tech Stack

<div align="center">

**Perception**

![YOLO](https://img.shields.io/badge/YOLOv5-00FFFF?style=flat-square&logo=yolo&logoColor=black)
![ONNX](https://img.shields.io/badge/ONNX_Runtime-005CED?style=flat-square&logo=onnx&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![LiDAR](https://img.shields.io/badge/LiDAR_Clustering-14c7ae?style=flat-square)
![Calib](https://img.shields.io/badge/LiDAR--Camera_Calibration-14c7ae?style=flat-square)
![IMX500](https://img.shields.io/badge/IMX500_AI_Camera-14c7ae?style=flat-square)

**Planning / Control**

![FSM](https://img.shields.io/badge/FSM-ff9f40?style=flat-square)
![PID](https://img.shields.io/badge/PID-ff9f40?style=flat-square)
![Stanley](https://img.shields.io/badge/Stanley_Control-ff9f40?style=flat-square)
![Path](https://img.shields.io/badge/경로_생성-ff9f40?style=flat-square)
![Safeguard](https://img.shields.io/badge/Safe--guard_로직-ff9f40?style=flat-square)

**Middleware / Comm**

![ROS](https://img.shields.io/badge/ROS-22314E?style=flat-square&logo=ros&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white)
![rosserial](https://img.shields.io/badge/rosserial_(STM32H7_포팅)-22314E?style=flat-square)
![MQTT](https://img.shields.io/badge/MQTT_(Paho)-660066?style=flat-square&logo=mqtt&logoColor=white)
![DMA](https://img.shields.io/badge/DMA_%2F_IDLE_Interrupt-660066?style=flat-square)

**Edge AI / Embedded**

![RPi](https://img.shields.io/badge/Raspberry_Pi_4%2F5-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![STM32](https://img.shields.io/badge/STM32H7-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![DeepX](https://img.shields.io/badge/DEEPX_NPU-00A19A?style=flat-square)
![Hailo](https://img.shields.io/badge/Hailo--8L-00A19A?style=flat-square)
![PCA9685](https://img.shields.io/badge/PCA9685-00A19A?style=flat-square)
![IMU](https://img.shields.io/badge/IMU_%2F_Touch_Sensor-00A19A?style=flat-square)

**Mapping / Fusion**

![Cartographer](https://img.shields.io/badge/Cartographer_SLAM-3776AB?style=flat-square)
![Fusion](https://img.shields.io/badge/센서_퓨전-3776AB?style=flat-square)
![Odometry](https://img.shields.io/badge/Odometry-3776AB?style=flat-square)
![DigitalTwin](https://img.shields.io/badge/디지털_트윈-3776AB?style=flat-square)

**Interface / Data**

![STT](https://img.shields.io/badge/STT_%2F_TTS-6F4E9C?style=flat-square)
![WakeWord](https://img.shields.io/badge/Wake_Word-6F4E9C?style=flat-square)
![LLM](https://img.shields.io/badge/Local_LLM-6F4E9C?style=flat-square)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=googlemediapipe&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram_API-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![Dashboard](https://img.shields.io/badge/실시간_대시보드-6F4E9C?style=flat-square)

</div>

---

### 📌 Featured Projects

<details open>
<summary><b>🐾 시각장애인을 위한 안내 보조 로봇 — BADUK</b></summary>
<br/>

목줄과 조이스틱으로 자연스럽게 유도하는 안내로봇. Raspberry Pi(인지·경로·음성)와 STM32(구동·조향·안전정지)가 rosserial로 연결된 이기종 실시간 제어 시스템입니다.

`Raspberry Pi` `STM32H7` `ROS/rosserial` `YOLO` `LiDAR` `IMU` `Porcupine` `STT/TTS`

🔗 [github.com/sunmaan22/guide_robot_for_blind_person](https://github.com/sunmaan22/guide_robot_for_blind_person)
</details>

<details>
<summary><b>🎥 LiDAR-CCTV 융합 디지털 트윈 안전 모니터링 · Personal Cam</b></summary>
<br/>

DeepX NPU 기반 YOLO로 작업자·PPE를 인식하고, LiDAR와 CCTV를 정합해 관제 좌표계로 통합한 뒤 MQTT로 실시간 대시보드에 전송하는 산업 안전 시스템. IMX500+Hailo-8L 웨어러블 카메라로 제스처 핫키·낙상 감지·LLM 일일 리포트를 처리하는 Personal Cam 서브프로젝트를 포함합니다.

`Raspberry Pi 5` `DEEPX NPU` `Hailo-8L` `IMX500` `ROS2` `Cartographer SLAM` `Local LLM` `MQTT`

🔗 [github.com/sunmaan22/personal_cam](https://github.com/sunmaan22/personal_cam)
</details>

<details>
<summary><b>🚗 자율주행 인지·판단·제어 — SHARK 2024 → FMA 2024 → FMA 2025</b></summary>
<br/>

성남시 SHARK 자율주행대회부터 MORAI 시뮬레이터 기반 HL Future Mobility Award 2024·2025까지, 시뮬레이션 환경에서 3개 대회에 걸쳐 단계적으로 발전시킨 인지·계획·제어 스택. YOLOv10+ByteTrack 인지, DBSCAN LiDAR 클러스터링, Lattice Planner 정적 회피, Pure Pursuit+PID 경로 추종까지 자율주행 스택 전 구간을 직접 구현했습니다.

`ROS1` `MORAI Simulator` `YOLOv10+ByteTrack` `DBSCAN` `Lattice Planner` `Pure Pursuit` `MQTT`

🔗 [github.com/sunmaan22/FMA_2025](https://github.com/sunmaan22/FMA_2025)
</details>

<details>
<summary><b>🏁 국민대 SDV 자율주행 경진대회 — Xycar 예선 주행 코드</b></summary>
<br/>

GPS 없이 카메라·라이다만으로 차선 추종·라바콘 회피·전방 차량 추월·신호등 인식을 처리한 예선 주행 스택. 추월 로직 하드코딩 회고와 본선(비전 단독 차선 추종) 실패 회고를 함께 정리했습니다.

`ROS1` `OpenCV (HSV+Hough)` `적응형 PID` `2D LiDAR` `Pure Pursuit` `YOLOv5n`

🔗 [github.com/sunmaan22/Kookmin_SDV](https://github.com/sunmaan22/Kookmin_SDV)
</details>

<details>
<summary><b>🌐 Portfolio — sunmaan22.github.io</b></summary>
<br/>

위 프로젝트들을 인지·판단·제어 관점에서 정리한 개인 포트폴리오 사이트. 백엔드 없이 정적 다중 페이지로 GitHub Pages에 배포되어 있습니다.

`HTML/CSS/JS` `GitHub Pages` `Mermaid`

🔗 [sunmaan22.github.io](https://sunmaan22.github.io)
</details>

---

### 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=sunmaan22&show_icons=true&hide_title=true&hide_border=true&bg_color=00000000&title_color=14c7ae&icon_color=14c7ae&text_color=8b9096" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sunmaan22&layout=compact&hide_border=true&bg_color=00000000&title_color=14c7ae&text_color=8b9096" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=sunmaan22&hide_border=true&background=00000000&ring=14c7ae&fire=ff9f40&currStreakLabel=14c7ae" />

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0c0f,100:14c7ae&height=120&section=footer" />

</div>
