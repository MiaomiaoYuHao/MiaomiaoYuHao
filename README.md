# Casey · lina130

Embedded systems · robotics · tactile sensing · real-time control · motion capture.

GitHub: [@lina130](https://github.com/lina130)

## Featured projects

### Xunbu Mocap System

Multi-camera optical motion capture and hand tracking for Windows, including camera calibration, 2D detection, triangulation, IEKF tracking, hand-skeleton estimation, `.pcrec` recording/replay, and Unity integration.

[Repository](https://github.com/lina130/Mocap_System) · [Demo](https://github.com/lina130/Mocap_System/blob/main/demo/Xunbu%20Demo%E6%9C%80%E7%BB%88%E7%89%88.mp4)

### OSMO Glove Toolkit

Custom Bowie/OSMO tactile-glove firmware variants with 3D magnetic-force and attitude/yaw pipelines, Windows host applications, calibration, diagnostics, replay tools, and reproducible release images.

[Repository](https://github.com/lina130/osmo-glove-toolkit)

### Motion Capture Glove

STM32 glove firmware together with Unity host software for motion-capture and glove interaction experiments.

[Repository](https://github.com/lina130/Motion_Capture_Glove)

## Public repositories

### Motion capture, robotics and sensing

| Repository | Stack | Focus |
|---|---|---|
| [Mocap_System](https://github.com/lina130/Mocap_System) | C++ / Qt6 | Multi-camera motion capture, hand tracking, calibration, recording/replay and Unity output |
| [osmo-glove-toolkit](https://github.com/lina130/osmo-glove-toolkit) | C / Python | 3D magnetic-force and attitude/yaw glove firmware, host tools and release images |
| [Motion_Capture_Glove](https://github.com/lina130/Motion_Capture_Glove) | C / Unity | STM32 glove firmware and Unity host software |
| [osmo_tactile_glove](https://github.com/lina130/osmo_tactile_glove) | C / C++ | Open-source tactile glove for robotics research |
| [Fabric_Recognition_and_Material_Demo](https://github.com/lina130/Fabric_Recognition_and_Material_Demo) | Python | Tactile + acoustic fabric/material recognition and CNC demonstration |
| [AI_cat](https://github.com/lina130/AI_cat) | C++ | ESP32 multimodal bionic robotic cat with audio, cloud emotion analysis and servo feedback |
| [Camera_dashboard](https://github.com/lina130/Camera_dashboard) | C++ | ESP32-S3 FreeRTOS camera exposure control panel |
| [Agriculture_Monitoring](https://github.com/lina130/Agriculture_Monitoring) | Python | Raspberry Pi environmental monitoring for air, soil and rain |
| [Simulated-Computer](https://github.com/lina130/Simulated-Computer) | C | Von Neumann computer simulation using two independent microcontrollers |

### Embedded systems and electronics

| Repository | Stack | Focus |
|---|---|---|
| [stm32test](https://github.com/lina130/stm32test) | C | STM32 minimum-system applications and experiments |
| [EC2026](https://github.com/lina130/EC2026) | C | Electronics competition and embedded-system work |
| [NUEDC_Topic](https://github.com/lina130/NUEDC_Topic) | Docs | Collected National Undergraduate Electronic Design Contest topics, 1994–2025 |
| [nuedc-2026-h-ball-balance](https://github.com/lina130/nuedc-2026-h-ball-balance) | Python | Raspberry Pi 5 ball-and-beam control system with camera, stepper motor, encoder and PID |

### Software, OS and IoT

| Repository | Stack | Focus |
|---|---|---|
| [OS_Programming](https://github.com/lina130/OS_Programming) | C | Operating-system programming coursework and experiments |
| [courses_add_drop](https://github.com/lina130/courses_add_drop) | Python / Flask | Course-selection system with recommendations, schedule updates and conflict detection |
| [Hospital_Registration_Terminal](https://github.com/lina130/Hospital_Registration_Terminal) | Python / Tkinter | Hospital registration and department queue scheduling |
| [SmartCity_IoT_Project](https://github.com/lina130/SmartCity_IoT_Project) | Python | Smart-city sensor and network resource management with graph/Dijkstra algorithms |

### Games and interactive demos

| Repository | Stack | Focus |
|---|---|---|
| [shenriji-kitchen-demo](https://github.com/lina130/shenriji-kitchen-demo) | JavaScript | Mobile-web playable demo for the “深日记” kitchen game |
| [shenriji-kitchen-dev](https://github.com/lina130/shenriji-kitchen-dev) | GDScript / Godot 4 | Life-management kitchen game development and playable prototype |

## Reproducibility

The OSMO force-firmware build is verified end to end against a pinned upstream commit. The custom attitude source and release images are included in the toolkit.

~~~powershell
git clone https://github.com/lina130/osmo-glove-toolkit.git
cd osmo-glove-toolkit
.\scripts\reproduce_all.ps1
~~~

Expected result:

~~~text
REPRODUCTION_PASS=True
~~~