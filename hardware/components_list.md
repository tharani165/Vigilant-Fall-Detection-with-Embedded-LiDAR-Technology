# Hardware Components

Bill of materials for the Vigilant fall detection prototype, as described in the project's system design and patent documentation.

| Component | Model / Type | Role in the System |
|-----------|-------------|---------------------|
| LiDAR Sensor | RPLIDAR A1 | 360° 2D LiDAR used for continuous, privacy-preserving point-cloud sensing of the monitored area |
| Edge Compute | NVIDIA Jetson Nano | On-device processing board for running the fall detection pipeline locally |
| Camera | USB camera | Selectively activated to capture visual confirmation once a possible fall is flagged |
| Power Supply | 5V regulated USB-C power supply | Powers the Jetson Nano and connected peripherals |
| Networking | USB/Wi-Fi network adapter | Provides connectivity for sending alert notifications |

## Notes

- Component costs are not published here, as they vary by supplier and were not independently verified for this repository.
- Full technical specifications (scan range, update rate, power draw, etc.) are documented in the patent application and reference paper in [docs/](../docs/), not restated here to avoid duplication or inaccuracy.
- This is a components list for a research prototype, not a validated production bill of materials.

## References

- RPLIDAR A1: https://www.slamtec.com/en/Lidar/A1
- NVIDIA Jetson Nano: https://developer.nvidia.com/embedded/jetson-nano
