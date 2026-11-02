Project MicroFly

An open source hardware, firmware, and test-rig repository for an ultra-lightweight insect scale flapping wing micro robot.

System Architecture:

Actuation Mechanism: Electromagnetic coils 40 AWG copper wire driven against micro Neodymium magnets with Nitinol hinges and Kapton wing membranes.

Flapping Kinematics: Designed for approximately 35 degree stroke amplitude using a 24:1 lever ratio drive setup.

Onboard Electronic:
  * Microcontroller: TI MSPM0C1104
  * Electromagnet Driver: TI DRV8836 Dual H-Bridge Driver
  * IMU: ICM-42688-P
  * Power: 30mAh 3.7V LiPo

Test Bench: 2mm Carbon Fiber lever assembly integrated with a high-speed global shutter camera (Arducam OV9281 @ 120fps), strobe illumination, precision thrust logging.
