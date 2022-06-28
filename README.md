# stm32f3disco-rs-lab

Personal lab monorepo containing Rust applications and crates for the STMicroelectronics
[STM32F3DISCOVERY](https://www.st.com/en/evaluation-tools/stm32f3discovery.html) development board,
featuring the 72 MHz [STM32F303xB/STM32F303xC](https://www.st.com/resource/en/datasheet/stm32f303vc.pdf)
family of Arm(R) Cortex(R)-M4 MCUs with FPU.

---

## MCU Description

The STM32F303xB/STM32F303xC family is based on the high-performance Arm(R) Cortex(R)-
M4 32-bit RISC core with FPU operating at a frequency of up to 72 MHz, and embedding a
floating point unit (FPU), a memory protection unit (MPU) and an embedded trace macrocell
(ETM). The family incorporates high-speed embedded memories (up to 256 Kbytes of Flash
memory, up to 40 Kbytes of SRAM) and an extensive range of enhanced I/Os and
peripherals connected to two APB buses.

The devices offer up to four fast 12-bit ADCs (5 Msps), seven comparators, four operational
amplifiers, up to two DAC channels, a low-power RTC, up to five general-purpose 16-bit
timers, one general-purpose 32-bit timer, and two timers dedicated to motor control. They
also feature standard and advanced communication interfaces: up to two I2Cs, up to three
SPIs (two SPIs are with multiplexed full-duplex I2Ss), three USARTs, up to two UARTs, CAN
and USB. To achieve audio class accuracy, the I2S peripherals can be clocked via an
external PLL.

---

## Getting Started

### Required Hardware

>The following instructions assume, for simplicity, the existence of an available USB Type-A port on the host device. Use of an adapter providing a USB Type-A port to USB-C connector should also work.

A **USB Mini-B to Type-A cable** is required for connection between the development board and the host device. The USB Mini-B connector plugs into the USB Mini-B port, flat side up, i.e., away from the PCB.

![USB Mini-B port](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/USB_Mini-B_receptacle.svg/134px-USB_Mini-B_receptacle.svg.png)

![USB Type-A connector](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c5/USB_Type-A_receptacle_Black.svg/150px-USB_Type-A_receptacle_Black.svg.png)

### Required Software

#### macOS

>TODO

#### Windows

>TODO

#### Linux

>TODO

---

## License

[MIT License](https://spdx.org/licenses/MIT.html)

---

`./README.md`
