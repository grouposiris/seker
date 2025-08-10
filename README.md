<h2> seker: SPI Slave IP Core </h2>

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

<p align="center">
  <img src="docs/images/results/seker_logo.png" width=250 alt="Seker IP logo">
</p>

## Introduction

**Seker** is a high-performance **SPI Slave IP core** designed for seamless integration into FPGA and ASIC designs.  
It enables reliable communication with SPI masters, making it ideal for use as a standalone peripheral interface or as a core component in protocol bridge designs.

The Seker IP core supports all standard SPI clock modes, flexible data framing, and robust error handling.  
It is optimized for low-latency operation, ensuring dependable performance even in high-speed applications.  
As part of a modular IP ecosystem, Seker can be integrated directly into larger projects such as SPI-to-APB, SPI-to-I²C, or SPI-to-UART bridges.

Key features of Seker include:
- **Full SPI Slave Support:** Compatible with SPI modes 0, 1, 2, and 3 (CPOL/CPHA configurable).
- **Configurable Data Frame Size:** Supports variable data widths for different application needs.
- **High-Speed Operation:** Designed for reliable operation at high SPI clock frequencies.
- **FIFO Buffers:** Separate transmit and receive FIFOs for smooth, continuous data transfers.
- **Low Latency:** Optimized to minimize response delays from master requests.
- **Error Detection:** Flags overrun, underrun, and frame alignment errors.
- **Interrupt Support:** Event-driven signaling for received data, transmission completion, and errors.
- **Flexible Integration:** Simple interface for direct connection to internal logic or standard bus wrappers.

Seker is delivered with a verification suite to validate functionality and performance across multiple configurations.  
It is suitable for embedded systems, communication modules, and as the SPI endpoint in multi-protocol bridges.

Refer to the [documentation](docs/) for integration instructions, configuration parameters, and simulation examples.
