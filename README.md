# Casey · lina130

Embedded systems, robotics, tactile sensing, and real-time control.

## Featured project

### OSMO Magnet 3D Force

Magnetometer-based 3D force visualization and reproducible BowieGlove firmware stability work for the OSMO tactile glove.

- Real-time `Fx`, `Fy`, `Fz`, and `|F|`
- XY, XZ, and YZ vector projections
- Hard/soft-iron calibration
- Repeated-rubbing six-direction calibration
- BHI360 FIFO/reset recovery and USB stall recovery
- Byte-for-byte reproducible firmware build
- Prebuilt HEX/BIN release assets

[Repository](https://github.com/lina130/osmo-magnet-3d-force) · [v0.1.0 release](https://github.com/lina130/osmo-magnet-3d-force/releases/tag/v0.1.0)

## Selected projects

- [Mocap_System](https://github.com/lina130/Mocap_System) - multi-sensor human motion capture system and demo.
- [Camera_dashboard](https://github.com/lina130/Camera_dashboard) - FreeRTOS dual-core ESP32-S3 camera exposure controller.
- [AI_cat](https://github.com/lina130/AI_cat) - ESP32 multimodal bionic robotic cat.
- [Agriculture_Monitoring](https://github.com/lina130/Agriculture_Monitoring) - Raspberry Pi environmental monitoring system.
- [Simulated-Computer](https://github.com/lina130/Simulated-Computer) - Von Neumann computer simulation using two microcontrollers.
- [courses_add_drop](https://github.com/lina130/courses_add_drop) - Flask/SQLite course-selection system.
- [OS_Programming](https://github.com/lina130/OS_Programming) - operating-system programming work.

## Reproducibility

For `osmo-magnet-3d-force`, a fresh clone of the pinned upstream firmware, patch application, clean build, and SHA256 comparison are automated:

```powershell
.\scripts\reproduce_all.ps1
```

Expected result:

```text
REPRODUCTION_PASS=True
```