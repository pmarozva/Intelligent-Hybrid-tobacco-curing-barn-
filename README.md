# Intelligent Hybrid Solar–LPG/Biogas Tobacco Curing Barn

**Team 10, Mechatronics Final-Year Capstone** | Supervisor: E. Sibanda

## Overview
Design and development of a lab-scale tobacco curing system that replaces wood-fired curing and manual monitoring. It combines hybrid solar and gas heating, automated tray loading and unloading, and IoT-based environmental control with remote monitoring. The prototype uses LPG to stand in for biogas during demonstration.

## Objectives
1. Hybrid solar-gas heating prototype that can run on either source or both.
2. Automated loading and unloading of tobacco racks.
3. IoT control and monitoring of temperature, humidity, curing stage and alerts.

## Curing stage targets
| Stage | Temperature |
| --- | --- |
| Yellowing | 35–38°C |
| Colour fixing | 38–50°C |
| Stem drying | 50–70°C |

## Key milestones
| Milestone | Date |
| --- | --- |
| Design Review | 30/11/26 |
| Preliminary Demo | 26/02/27 |
| Integration Check | 05/03/27 |
| Final Demo | 30/04/27 |

## Tech stack
Arduino and ESP32, DHT22 sensors, A4988 stepper drivers, MPPT solar charging with a 12V battery, SolidWorks (mechanical), Proteus (electronics simulation), MQTT/HTTP with JSON telemetry for the dashboard.

## Repository structure (suggested)
```
/docs        Charter, work plan, design report, meeting minutes
/cad         SolidWorks parts, assemblies, drawings
/electronics Proteus schematics and simulations, wiring diagrams
/firmware    Arduino and ESP32 code
/dashboard   Remote monitoring interface
/testing     Test plan, test data, results
```

## Team
Lynos T Pasi (Project Manager), Takudzwa Madoda, Kelvin T. Makacha, Brighton Njeke, Tashinga E Matarirano, Wayne Mukucha, Justice Tayengwa, Takura Mupxetedzi, Thabani J. Chasokela, Precious S. Marozva

## Collaboration rules
- Work on a branch per task (for example `cad/chamber-frame`) and merge through pull requests reviewed by the task owner and one other member.
- Use clear commit messages and include the work package ID, for example `3.2 add chamber door model`.
- Keep large binary files (SolidWorks, Proteus) in the correct folder, and give each save a version suffix or use Git LFS.
