# Margeaux Corrigan

Electrical engineering student at Brown University, Class of 2029. I build embedded
systems from the register level up: bare-metal C and Ada, no vendor HAL, verified on
real hardware.

**Now:** test infrastructure for the driver stack below (host-side unit tests, a pytest
hardware-in-the-loop harness, CI), then a custom flight computer to run it.

### Projects

**[Bare-Metal-Drivers](https://github.com/MargXX/Bare-Metal-Drivers)**
From-scratch C drivers for the RP2040, written against the datasheet. GPIO, SysTick,
UART, I2C, and BMP390 complete and hardware-verified with a logic analyzer and OpenOCD.
Platform layer isolates register maps for a future STM32 port.

**[IREC 2025-2026 Payload Firmware](https://github.com/Brown-Rocketry/IREC-2025-2026/tree/main/terrarium_pico)**
Bare-metal Ada flight data logger on an RP2040, built as sole developer. Polls an LSM9DS1 and BMP390 over I2C and
logs to W25Q128 SPI flash. Flew on a live high-power launch and logged 25 hours of
sensor data, including flight loads above 12 G.

**[margxx.github.io](https://margxx.github.io)**
Portfolio with build photos, flight data plots, and project writeups.

### Skills

- **Embedded:** bare-metal C and Ada, RP2040, STM32, I2C, SPI, UART, interrupts
- **Verification:** Saleae logic analyzer (sigrok/PulseView), OpenOCD, CMSIS-DAP
- **Hardware:** KiCad schematics, soldering, SolidWorks, Fusion 360, FEA
- **Toolchain:** GNAT ARM, Alire, CMake, Git

Embedded firmware mentee with AdaCore (bare-metal Ada on STM32G431). UTRA research
fellow, Brown Interactive 3D Vision & Learning Lab.

margeaux_corrigan@brown.edu · [LinkedIn](https://www.linkedin.com/in/margeaux-corrigan/)
