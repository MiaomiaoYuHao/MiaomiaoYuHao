# Casey · lina130

Embedded systems, robotics, tactile sensing, and real-time control.

## Featured project

### OSMO Glove Toolkit

Custom firmware variants and Windows host tools for the OSMO/Bowie tactile glove.

- 3D magnetic force firmware and host application
- Custom 9-DoF attitude / magnetic-yaw firmware and host application
- Official Bosch NDOF single-magnet yaw variant
- Full compatible 6-DoF GAMERV build
- Raw preview, calibration, diagnostics, trace recording, replay, and verification tools
- Prebuilt HEX/BIN files with SHA256 checksums

[Repository](https://github.com/lina130/osmo-glove-toolkit) · [v0.2.0 release](https://github.com/lina130/osmo-glove-toolkit/releases/tag/v0.2.0)

## Selected projects

- [Mocap_System](https://github.com/lina130/Mocap_System) - multi-sensor human motion capture system and demo.
- [Camera_dashboard](https://github.com/lina130/Camera_dashboard) - FreeRTOS dual-core ESP32-S3 camera exposure controller.
- [AI_cat](https://github.com/lina130/AI_cat) - ESP32 multimodal bionic robotic cat.
- [Agriculture_Monitoring](https://github.com/lina130/Agriculture_Monitoring) - Raspberry Pi environmental monitoring system.
- [Simulated-Computer](https://github.com/lina130/Simulated-Computer) - Von Neumann computer simulation using two microcontrollers.
- [courses_add_drop](https://github.com/lina130/courses_add_drop) - Flask/SQLite course-selection system.
- [OS_Programming](https://github.com/lina130/OS_Programming) - operating-system programming work.

## Reproducibility

The force firmware build is verified end to end against a pinned upstream commit. The custom attitude source and all release images are included in the toolkit.

~~~powershell
git clone https://github.com/lina130/osmo-glove-toolkit.git
cd osmo-glove-toolkit
.\scripts\reproduce_all.ps1
~~~

Expected result:

~~~text
REPRODUCTION_PASS=True
~~~
