<div align="center">

![Header](https://capsule-render.vercel.app/api?type=transparent&height=200&section=header&text=Picket&fontSize=80&fontAlignY=40&desc=Autonomous%20Driving%20%7C%20Perception%20%7C%20SLAM%20%7C%20Robotics&descSize=18&descAlignY=62&fontColor=6366F1)

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/johns27)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/StrPicket)
[![Email](https://img.shields.io/badge/-Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:ejohns.ipod@gmail.com)

![Profile Views](https://komarev.com/ghpvc/?username=StrPicket&color=F97316&style=for-the-badge&label=PROFILE%20VIEWS)
![Status](https://img.shields.io/badge/STATUS-OPEN%20TO%20SELF--DRIVING%20%26%20GEOMETRIC%20VISION%20ROLES-22C55E?style=for-the-badge&labelColor=555555)

</div>

---

<table>
<tr>
<td valign="top" width="60%">

<h2>About Me</h2>

<p>Robotics &amp; Digital Systems Engineering student at <b>Tecnológico de Monterrey</b>, graduating in <b>December 2026</b> and focused on <b>autonomous driving</b>. I build the full stack of a self-driving robot: <b>vision-based perception</b> (YOLOv8, fisheye calibration, AprilTags), <b>LiDAR SLAM</b> and <b>EKF sensor fusion</b>, planning and control, all integrated on-board with <b>ROS 2</b> on Jetson, STM32 and FPGA hardware.</p>

<p>I've led 5-person teams through Agile/Scrum sprints with V-Model verification, taking systems from simulation to the real robot, and led a team at the international <b>Quanser Mechatronics Challenge</b> in Canada (2025).</p>

<p>
<img src="https://img.shields.io/badge/Autonomous%20Driving-F97316?style=flat-square" alt="Autonomous Driving">
<img src="https://img.shields.io/badge/Computer%20Vision-06B6D4?style=flat-square" alt="Computer Vision">
<img src="https://img.shields.io/badge/SLAM-8B5CF6?style=flat-square" alt="SLAM">
<img src="https://img.shields.io/badge/Sensor%20Fusion-4ECDC4?style=flat-square" alt="Sensor Fusion">
<img src="https://img.shields.io/badge/ROS%202-CE0000?style=flat-square" alt="ROS 2">
<img src="https://img.shields.io/badge/Embedded%20Systems-475569?style=flat-square" alt="Embedded Systems">
</p>

</td>
<td align="center" valign="middle" width="40%">

<img src="assets/about-illustration.svg" width="340" alt="Autonomous vehicle with LiDAR and camera perception">

</td>
</tr>
</table>

---

## Experience & Leadership

🦾 **Team Leader — Quanser Mechatronics Challenge** · Markham, Ontario, Canada · Nov 2025
> Built a robotic arm from scratch with a YOLO/OpenCV cube-sorting pipeline and hand-gesture teleoperation. Earned a Quanser training certification.

👨‍🏫 **Robotics Instructor (Social Service)** · Tecnológico de Monterrey / SMALC · 2025
> Taught robotics, programming and electronics through hands-on projects.

🎓 **B.Eng. Robotics and Digital Systems** · Tecnológico de Monterrey · Expected Dec 2026

---

## Featured Projects

### 🚗 [Autonomous Driving PuzzleBot](https://github.com/StrPicket/Puzzlebot_Challenge)
*Jan – Jun 2025 · Team lead (5 people)*

<div align="center">

<a href="https://www.youtube.com/watch?v=VRI7v477p8M"><img src="https://img.youtube.com/vi/VRI7v477p8M/hqdefault.jpg" width="560" alt="Autonomous Driving PuzzleBot demo"></a>
<br><sub>▶ Click to watch the demo</sub>

</div>

Led the development of an end-to-end autonomous driving system on a fisheye-camera PuzzleBot, from perception to decision-making and control, running fully on-board as a modular ROS 2 architecture. I owned the deep learning workflow for traffic-sign recognition (data collection and labeling, training, real-time deployment on embedded hardware), integrated with classical vision for lane and traffic-light perception, and designed a finite-state machine that fuses the perception signals and prioritizes safe behavior in critical maneuvers.

**Tools:** ![ROS 2](https://img.shields.io/badge/ROS%202-CE0000?style=flat-square&logo=ros&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![YOLOv8](https://img.shields.io/badge/YOLOv8-00B8D4?style=flat-square) ![Jetson Nano](https://img.shields.io/badge/Jetson%20Nano-76B900?style=flat-square&logo=nvidia&logoColor=white)

**Concepts & skills:** traffic-sign recognition, lane and traffic-light detection, fisheye camera, finite-state machines, modular ROS 2 architecture, field testing, team leadership.

<br>
<br>

---

<br>
<br>

### 📦 Autonomous Warehouse PuzzleBot
*Jan – Jun 2026 · Team lead (5 people)*

Led an autonomous warehouse forklift project using Agile/Scrum sprints with V-Model verification, coordinating system integration and testing on the real robot. The robot builds the warehouse map from scratch with LiDAR particle-filter SLAM, plans routes with semantic A\*/Dijkstra planning and Bug2 reactive avoidance, and localizes with an EKF that fuses fisheye-camera pose from AprilTags/QR markers (with outlier gating) for pallet alignment. A ROS 2–FPGA lifting mechanism closes the loop, where I also debugged clock desynchronization and motor command latency across the stack.

**Tools:** ![ROS 2](https://img.shields.io/badge/ROS%202-CE0000?style=flat-square&logo=ros&logoColor=white) ![LiDAR](https://img.shields.io/badge/LiDAR-FF6B6B?style=flat-square) ![FPGA Tang Nano 20K](https://img.shields.io/badge/FPGA%20Tang%20Nano%2020K-8A2BE2?style=flat-square) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![AprilTag / QR](https://img.shields.io/badge/AprilTag%20/%20QR-4ECDC4?style=flat-square)

**Concepts & skills:** SLAM (particle filter), EKF sensor fusion, camera calibration, PnP pose estimation, A\*/Dijkstra, Bug2, SPI communication, Agile/Scrum, V-Model.

<br>
<br>

---

<br>
<br>

### 🚁 Cooperative UAVs for Oil-Leak Monitoring
*Aug – Dec 2025 · Technical lead (5 people)*

<div align="center">

<a href="https://www.youtube.com/watch?v=_xsIzY1pPvs"><img src="https://img.youtube.com/vi/_xsIzY1pPvs/hqdefault.jpg" width="560" alt="Cooperative UAVs demo"></a>
<br><sub>▶ Click to watch the demo</sub>

</div>

Defined the architecture of a cooperative two-UAV inspection system and integrated perception, control and inter-drone coordination. I trained and refined a multiclass YOLO segmentation model that feeds image-based visual servoing with PD control: the reconnaissance UAV logs hazards ranked by severity as waypoints, and a second UAV re-inspects, centers and verifies each one.

**Tools:** ![YOLO](https://img.shields.io/badge/YOLO-00B8D4?style=flat-square) ![Visual Servoing](https://img.shields.io/badge/Visual%20Servoing-F97316?style=flat-square) ![PD Control](https://img.shields.io/badge/PD%20Control-6366F1?style=flat-square)

**Concepts & skills:** instance segmentation, image-based visual servoing, PD control, multi-agent coordination, system architecture, technical leadership.

<br>
<br>

---

<br>
<br>

### 🦾 Quanser Mechatronics Challenge
*Nov 2–7, 2025 · Markham, Ontario, Canada · Team leader*

<div align="center">

<a href="https://www.youtube.com/watch?v=2HFREQfGqWA"><img src="https://img.youtube.com/vi/2HFREQfGqWA/hqdefault.jpg" width="560" alt="Quanser Mechatronics Challenge demo"></a>
<br><sub>▶ Click to watch the demo</sub>

</div>

Led the end-to-end development of a robotic arm built from scratch with Quanser's new actuators and sensors, covering system integration, control, testing and troubleshooting. I built a YOLO/OpenCV color-based detection pipeline for an autonomous cube-sorting sequence and extended it to hand-gesture teleoperation of the arm's joints and gripper. The project earned a training certification from Quanser.

**Tools:** ![YOLO](https://img.shields.io/badge/YOLO-00B8D4?style=flat-square) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![Quanser](https://img.shields.io/badge/Quanser-0A66C2?style=flat-square)

**Concepts & skills:** actuator and sensor integration, robotic arm control, color-based object detection, gesture teleoperation, troubleshooting under time pressure, team leadership.

<br>
<br>

---

<br>
<br>

### 🚜 Autonomous Tractor Prototype (John Deere)
*Aug – Dec 2024 · Industry partner: John Deere*

Designed the embedded system of an autonomous tractor prototype: PWM motor control with encoders, GPS waypoint navigation, IMU motion tracking, CAN communication between devices and NRF24L01 wireless telemetry.

**Tools:** ![STM32H755](https://img.shields.io/badge/STM32H755-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white) ![CAN Bus](https://img.shields.io/badge/CAN%20Bus-FF4500?style=flat-square) ![GPS / IMU](https://img.shields.io/badge/GPS%20/%20IMU-4ECDC4?style=flat-square) ![NRF24L01](https://img.shields.io/badge/NRF24L01-555555?style=flat-square)

**Concepts & skills:** embedded firmware, PWM and encoder control, waypoint navigation, inertial sensing, CAN bus, wireless telemetry.

<br>
<br>

---

<br>
<br>

### ⚙️ Embedded Systems Projects
*Academic projects*

Built a real-time vehicle simulation with FreeRTOS tasks, queues and semaphores plus a Raspberry Pi GUI, and developed an FPGA-based vehicle-control interface with accelerometer steering and a UART link to Unity.

**Tools:** ![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white) ![FreeRTOS](https://img.shields.io/badge/FreeRTOS-4CAF50?style=flat-square) ![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-C51A4A?style=flat-square&logo=raspberry-pi&logoColor=white) ![FPGA (VHDL)](https://img.shields.io/badge/FPGA%20(VHDL)-5E35B1?style=flat-square) ![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)

**Concepts & skills:** real-time operating systems, task synchronization, hardware/software co-design, UART, GUI development.

---

## Tech Stack

**Programming & Vision**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white) ![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white) ![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white) ![Verilog](https://img.shields.io/badge/Verilog-8A2BE2?style=for-the-badge) ![OpenCV](https://img.shields.io/badge/OpenCV-228B22?style=for-the-badge&logo=opencv&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**Autonomous Systems**

![ROS2](https://img.shields.io/badge/ROS%202-CE0000?style=for-the-badge&logo=ros&logoColor=white) ![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge) ![Gazebo](https://img.shields.io/badge/Gazebo-239120?style=for-the-badge&logo=gazebo&logoColor=white) ![LiDAR](https://img.shields.io/badge/LiDAR-FF6B6B?style=for-the-badge) ![EKF](https://img.shields.io/badge/EKF-4ECDC4?style=for-the-badge)

**Hardware & Communication**

![Jetson](https://img.shields.io/badge/Jetson-76B900?style=for-the-badge&logo=nvidia&logoColor=white) ![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white) ![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-C51A4A?style=for-the-badge&logo=raspberry-pi&logoColor=white) ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white) ![CAN](https://img.shields.io/badge/CAN%20Bus-FF4500?style=for-the-badge) ![SPI/I2C/UART](https://img.shields.io/badge/SPI%20%7C%20I2C%20%7C%20UART-555555?style=for-the-badge)

**Tools**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white) ![Simulink](https://img.shields.io/badge/Simulink-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)

---

## Currently

🔭 **Working on:** a vision-based autonomous driving project, with vision as the main source of perception.

🎯 **Looking for:** roles focused on **geometric vision** and **self-driving**.

![Geometric Vision](https://img.shields.io/badge/Geometric%20Vision-6366F1?style=flat-square) ![Self-Driving](https://img.shields.io/badge/Self--Driving-F97316?style=flat-square) ![Vision-Based Autonomy](https://img.shields.io/badge/Vision--Based%20Autonomy-06B6D4?style=flat-square)

---

<div align="center">

### Let's Connect

*Open to geometric vision & self-driving roles — graduating December 2026*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/johns27)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ejohns.ipod@gmail.com)


</div>
