Development Roadmap:

1) Test Stand Construction
  Build the test rig to measure thrust output and obtain data
  Objectives:
    Assemble the lever arm and clamp system.
    Mount the cameras and strobe illumination setup for optical capture.   
  Success critera: Record stable baseline data.


2) Actuator Iteration
  Test the actuators.
  Objectives:
    Experiment with different hinge sizes and wing dimensions
  Success critera Achieve a repeatable stroke.

3) Circuit Design
  Design and manufacture the dedicated onboard flight controller.
  Objectives:
    Finalize schematic and PCB layout incorporatig the TI MSPM0C1104 MCU, DRV8836 driver, and ICM-42688-P IMU.   
    Submit Gerber files for prototype manufacturing via JLCPCB.   

4) Tethered Flight Testing
  Test closed loop stability and sensor responsiveness under controlled conditions.
  Objectives:
    Tune PID control loops, actuator timing, and IMU feedback response.
  Success critera: Observe stable lift and attitude control while tethered.

5) Untethered Free Flight
  Objectives:
    Achieve Free flight.
    Publish CAD files, Source Code and Logs to GitHub.
