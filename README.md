# Cyclo


<p align="center"><strong>Unified Physical AI framework · ROBOTIS</strong></p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-Apache%202.0-blue?style=flat-square" alt="Apache 2.0" /></a>
  <a href="https://github.com/ROBOTIS-GIT"><img src="https://img.shields.io/static/v1?label=GitHub&message=ROBOTIS-GIT&color=181717&logo=github&style=flat-square" alt="ROBOTIS-GIT on GitHub" /></a>
</p>

Cyclo is a modular framework for building and operating **Physical AI** systems. It follows ROBOTIS’s open-source philosophy: put the building blocks in the open so **Physical AI** is easier for anyone to learn, integrate, and run on real hardware—not a closed, single-vendor path. It covers AI integration, action-data workflows, robot control, simulation, and operations. Private infrastructure (supervision, proprietary data, and similar) can plug in alongside the open public stack.

**Physical AI Lineup**

- [OpenMANIPULATOR](https://github.com/ROBOTIS-GIT/open_manipulator), [AI Worker](https://github.com/ROBOTIS-GIT/ai_worker), [ROBOTIS Hand](https://github.com/ROBOTIS-GIT/robotis_hand)

**Actuator products**

- [DYNAMIXEL](https://www.dynamixel.com/) series: DXL, DXL-X, DXL-P, DXL-Y, DXL-Q — interface stack: [Dynamixel SDK](https://github.com/ROBOTIS-GIT/DynamixelSDK)

## Framework overview

<p align="center">
  <img src="assets/cyclo_framework.png" alt="Cyclo framework overview" width="900" style="max-width: 100%; height: auto;" />
</p>

<p align="center"><em>Public modules, optional private stack, Physical AI lineup, and DYNAMIXEL actuator products.</em></p>

## Modules & repositories

| Module | Repository | Role | Release |
|--------|------------|------|---------|
| Cyclo Manager | [`cyclo_manager`](https://github.com/ROBOTIS-GIT/cyclo_manager) | Operations and system management | ![not released](https://img.shields.io/badge/release-not_released-lightgrey?style=flat-square) |
| Cyclo Brain | [`cyclo_brain`](https://github.com/ROBOTIS-GIT/cyclo_brain) | AI model integration and deployment | ![not released](https://img.shields.io/badge/release-not_released-lightgrey?style=flat-square) |
| Cyclo Data | [`cyclo_data`](https://github.com/ROBOTIS-GIT/cyclo_data) | Action data capture and curation | ![not released](https://img.shields.io/badge/release-not_released-lightgrey?style=flat-square) |
| Cyclo Control | [`cyclo_control`](https://github.com/ROBOTIS-GIT/cyclo_control) | Whole-body control and execution | [![release](https://img.shields.io/github/v/release/ROBOTIS-GIT/cyclo_control?style=flat-square)](https://github.com/ROBOTIS-GIT/cyclo_control/releases) |
| Cyclo Sim | `cyclo_sim` | Simulation and validation | ![not released](https://img.shields.io/badge/release-not_released-lightgrey?style=flat-square) |
| — | [`robotis_interfaces`](https://github.com/ROBOTIS-GIT/robotis_interfaces) | Shared interface definitions | [![release](https://img.shields.io/github/v/release/ROBOTIS-GIT/robotis_interfaces?style=flat-square)](https://github.com/ROBOTIS-GIT/robotis_interfaces/releases) |
| — | [`robotis_applications`](https://github.com/ROBOTIS-GIT/robotis_applications) | Application-level integrations and third-party dependencies | ![not released](https://img.shields.io/badge/release-not_released-lightgrey?style=flat-square) |

> Additional private or product-specific repositories may exist depending on deployment.

## Private stack

Not all components are part of the public release. Typical internal extensions:

- **Cyclo Supervisor** — robot supervision
- **Cyclo Hub** — private data infrastructure


## Quick links

| Resource | Description | Link |
|----------|-------------|------|
| Documentation | Product and software manuals | [AI Worker Website](https://ai.robotis.com/) |
| Discord | Community chat and support | [ROBOTIS Community](https://discord.gg/robotis) |
| YouTube | Tutorials and demos | [ROBOTIS Open Source Team](https://www.youtube.com/@ROBOTISOpenSourceTeam) |

## Contributing

Contributions are welcome via issues and pull requests in the relevant Cyclo repositories.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ROBOTIS-GIT/cyclo&type=Date)](https://star-history.com/#ROBOTIS-GIT/cyclo&Date)
