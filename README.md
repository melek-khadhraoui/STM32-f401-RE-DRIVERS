# STM32-f401-RE-DRIVERS

Minimal, clean, and bare-metal drivers for the **STM32F401RE** microcontroller.  
This repository provides a set of low-level peripheral drivers without relying on HAL &— ideal for learning and building lightweight embedded applications.

---

## 🧩 Implemented Drivers

| Peripheral | Description                       |
|------------|-----------------------------------|
| ✅ GPIO     | Configure input/output, modes, pull-up/down |
| ✅ EXTI     | External interrupts on GPIO lines |
| ✅ RCC      | Clock control and peripheral enable/disable |
| ✅ UART     | Serial communication (TX/RX)     |
| ✅ SPI      | SPI master mode driver           |
| ✅ I2C      | I2C master mode minimal driver    |
| ✅ ADC      | Single-channel analog input read  |

Each driver is built with a focus on:
- Direct register access
- Minimal abstraction
- Readability
- Simplicity
