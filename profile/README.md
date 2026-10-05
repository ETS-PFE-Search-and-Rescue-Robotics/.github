# ÉTS PFE — Search & Rescue Robotics

Coordinated **aerial drone + ground rover** system for search and rescue, built
as a final-year engineering project (PFE) at ÉTS. The drone maps an environment
and localizes the rover; the rover then drives autonomously to a chosen target
while avoiding obstacles.

🌐 **Project site:** https://ets-pfe-search-and-rescue-robotics.github.io
📖 **Detailed docs:** https://github.com/ETS-PFE-Search-and-Rescue-Robotics/documentation

## Repositories
| Repo | What it is |
|------|------------|
| [documentation](https://github.com/ETS-PFE-Search-and-Rescue-Robotics/documentation) | Setup guides, hardware notes, incident reports |
| [drone](https://github.com/ETS-PFE-Search-and-Rescue-Robotics/drone) | VOXL 2 / Starling 2 Max drone — control UI, VIO, calibration |
| [robot](https://github.com/ETS-PFE-Search-and-Rescue-Robotics/robot) | Waveshare UGV Flask web-control app (standalone stack) |
| [ugv_ws](https://github.com/ETS-PFE-Search-and-Rescue-Robotics/ugv_ws) | Rover ROS2 Humble autonomy stack (SLAM, Nav2, AprilTag) |

## Hardware at a glance
| Name | Role |
|------|------|
| Starling 2 Max | Drone airframe |
| VOXL 2 | Drone companion computer |
| Waveshare UGV | Ground rover |
| Jetson | Rover main computer |
| ESP32 | Rover motor/sensor sub-controller |

## Team lineage
- **A2025** — original (`LOG795-UAV-Search-and-Rescue`)
- **H2026** — `PFE-H2026-Search-and-rescue`
- **A2026** — current cohort; consolidated the above into this org

➡️ New to the project? Start with the
[handover page](https://ets-pfe-search-and-rescue-robotics.github.io/handover/).
