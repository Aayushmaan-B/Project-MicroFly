Project MicroFly

An open source hardware, firmware, and test-rig repository for an ultra-lightweight insect scale flapping wing micro robot.

System Architecture:
Actuation Mechanism: Electromagnetic coils 40 AWG copper wire driven against micro Neodymium magnets with Nitinol hinges and Kapton wing membranes.
Flapping Kinematics: Designed for approximately 35 degree stroke amplitude using a 24:1 lever ratio drive setup.
Onboard Electronic 
  * Microcontroller: TI MSPM0C1104
  * Actuator Driver: TI DRV8836 Dual H-Bridge Driver
  * Motion Sensor: ICM-42688-P 6-axis IMU
  * Power: 30mAh 3.7V LiPo via ultra-low dropout regulation
Characterization Test Bench: 2mm Carbon Fiber lever assembly integrated with a high-speed global shutter camera (Arducam OV9281 @ 120fps), strobe illumination, precision thrust logging.

Repository Layout
├── CAD Models/                3D models for test stand and micro-actuator assembly
├── Electronics/        Custom PCB schematic, board layouts, Gerber files
├── Firmware/           Source code for TI MSPM0 MCU pinouts and PWM driver timing
├── Docs/               Diagrams, BOM
└── README.md
