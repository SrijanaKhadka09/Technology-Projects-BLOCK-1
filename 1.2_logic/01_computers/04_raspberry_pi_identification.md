# Part 4 – Raspberry Pi Hardware Identification
Upload:
```
images/raspberry-pi/pi-board.jpg
images/raspberry-pi/labelled-pi-board.jpg
```
---

| Component | Function | Key Specification |
| --- | --- | --- |
| **SoC (System on Chip)** | Combines the main CPU, GPU, and system controller onto a single silicon chip to execute all system tasks. | Architecture (e.g., ARM64), clock speed (GHz), and number of core processing units. |
| **GPIO (General Purpose I/O)** | Physical pin headers used to interface directly with external sensors, LEDs, relays, and hardware accessories. | Pin count (e.g., 40-pin header), signal voltage (e.g., 3.3V logic level), and supported protocols (I2C, SPI, UART). |
| **USB** | Connects external peripherals like keyboards, mice, external storage, and USB adapters. | Interface standard (USB 2.0, USB 3.0/3.2 Gen 1) and data transfer rate (Mbps / Gbps). |
| **HDMI** | Outputs high-definition digital video and audio signals to an external monitor or display. | Output resolution and refresh rate support (e.g., 4K at 60Hz), connector form factor (Standard, Micro-HDMI). |
| **Power** | Supplies regulated electric power to run the single-board computer and attached peripherals. | Input voltage and current rating (e.g., 5V / 3A, 5V / 5A), port type (USB Type-C, Micro-USB, DC Barrel Jack). |
| **microSD** | Holds the operating system image, bootloader files, and persistent user storage. | Bus speed classification (e.g., UHS-I, Class 10), card reader interface, and maximum supported storage capacity. |
| **Network (Ethernet)** | Provides a wired network connection for high-speed local network and internet access. | Maximum throughput speed (e.g., Gigabit Ethernet 10/100/1000 Mbps) and PoE support capability. |
| **Wireless** | Offers built-in wireless networking and short-range device connectivity without external cables. | Wi-Fi standard (e.g., Dual-band 802.11ac / Wi-Fi 5) and Bluetooth version (e.g., Bluetooth 5.0 / BLE). |
---
## Reflection
Why are many components integrated into a single board in embedded computers such as the Raspberry Pi?
Write **100 words**.

In embedded computers such as the Raspberry Pi, integrating components onto a single board has considerable advantages, not the least of which is the fact that it can provide for extremely compact form factors in the case of portable electronics. The single-board design is frequently around a strong System-on-Chip that significantly reduces manufacturing and assembly expenses. Additionally, shorter physical distances between components means a shorter delay in signal propagation which in turn means a higher processing rate and higher performance. Last but not least, reduced wiring reduces heat and electricity consumption and eliminates the use of easily damaged physical connectors, leading to higher reliability and durability of the system over time.
