# Margeaux Corrigan

Freshman at Brown University (Class of 2029), studying Electrical Engineering. Interested in embedded systems and low-level hardware programming.

Currently working as Avionics Team Lead on [Brown Rocketry's IREC 2025-2026 entry](https://github.com/Brown-Rocketry/IREC-2025-2026) — bare-metal Ada firmware on an RP2040 for a flight data acquisition system, logging IMU and barometric data to SPI flash.

---

### Skills

- **Embedded:** Ada (bare-metal, `light-cortex-m0p` runtime), RP2040, STM32, I2C, SPI, UART
- **Languages:** Ada, Python, Java, MATLAB, C
- **CAD & Manufacturing:** SolidWorks, Fusion 360, FEA structural analysis, CAM toolpath generation
- **Tools:** Alire, OpenOCD, CMSIS-DAP, GNAT ARM toolchain, Git

---

### Projects

**[IREC 2025-2026 Payload Firmware](https://github.com/Brown-Rocketry/IREC-2025-2026/tree/main/terrarium_pico)** — Brown Rocketry  
Flight data logger for a high-power rocket payload. Polls LSM9DS1 IMU and BMP390 barometric sensor over I2C, packs 28-byte samples into 256-byte pages, and writes sequentially to a W25Q128 SPI flash chip. Written in Ada on the RP2040 bare-metal runtime with direct SVD register access for SPI and timing.
