# Remora RPi/W5500 LinuxCNC Adapter Board


RRW_LAB aka Remora RPi/W5500 LinuxCNC Adapter Board is a CNC controller board for use with LinuxCNC, in conjunction with a STM32 Blackpill board as the MCU to interface with Ethernet or Raspberry Pi. The board exists for the single purpose to promote the Remora project, with the design goals to be affordable, easy to make, and accessible while still retaining the core features.

- The board is not made for performance, it was made to work  adequately, with a simple setup.
- The board is still in beta testing; pinout, configs, firmware, formfactor, etc are likely to change in the future. 


- Documentation https://github.com/cakeslob/Remora-docs/blob/nucleo/docs/source/hardware/blackpill.rst

- Remora RPi SPI Firmware Source https://github.com/cakeslob/Remora/tree/rrw_lab

- Remora RPi SPI SD card Firmware Source https://github.com/cakeslob/Remora/tree/rrw_lab_sd

- Remora W5500 Ethernet Firmware Source  https://github.com/cakeslob/Remora-STM32F4xx-W5500/tree/bp2

- Pre-Compiled Firmware located in /FirmwareBin/

- LinuxCNC configurations and Components located in /LinuxCNC/

<img src="/boards.jpg" >

Features:


- 2 board variants 
- Ethernet or Raspberry Pi SPI interface
- STM32 Blackpill F4x1 as MCU
- 3 to 5 axis
- 8 Digital IO
- 1 Highspeed encoder
- 1 Spindle PWM


# Variants:

Stepstick Version: v0.355

Readme : 
https://github.com/cakeslob/RRW_LAB/blob/main/RRW_LAB_STEPSTICK/v0355/readme.md

- 3 Axis with Pololu stepper moter driver support (stepstick)
- 6 Inputs
- 2 Outputs
- 1 Highspeed encoder
- 1 Spindle PWM

 <img src="/photos/cncboard_ss_1c.jpg" > 

 DB25 Version:

- 5 axis support with DB25 CNC Breakout Board
- 5 Inputs
- 2 Outputs 
- 1 Highspeed encoder
- 1 Spindle PWM

 <img src="/photos/cncboard_db25_1a.jpg" > 

 # Interface: 

 - Raspberry Pi via SPI
 - Ethernet via W5500 Lite module (shown in photo below)

    <img src="/photos/cncboard_ss_2a.jpg" > 



