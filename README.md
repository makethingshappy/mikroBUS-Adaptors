# mikroBUS-Adaptors — mikroBUS™ Adaptors for Popular MCU Development Boards

The **mikroBUS-Adaptors** series by **makethingshappy** turns popular microcontroller development boards into complete devices: an on-board **mikroBUS™** slot for more than 2000 MikroElektronika Click® modules, a **HOST** connector for the **IoTextra** mezzanine system, an I²C connector, a temperature sensor and a wide-range 9–36 VDC power supply.

## Supported Modules

The series currently includes two adaptors:

- **Arduino Nano Adaptor**: For Arduino Nano format modules with a 3.3V signal level (Arduino® Nano 33 IoT, Nano 33 BLE Rev2, Nano RP2040 Connect, Nano ESP32, Nano R4, Nano Matter, Waveshare ESP32-S3-Nano, STM32 Nucleo-32).
- **Teensy Adaptor**: For Teensy 4.0, Teensy 3.2 and Teensy LC modules.

Further adaptors for other MCU development boards will be added to this repository.

---

## Key Features

### Power & Reliability

- **Wide Input Voltage**: Non-isolated 9VDC to 36VDC via a 2-pin 3.5mm terminal block, with reverse polarity and transient protection.
- **On-board Power Stages**: 5VDC converter (up to 1A) and 5VDC → 3.3VDC linear regulator.
- **Power Distribution**: Two 5VDC outputs (**5V-1**, **5V-2**) and an input voltage output (**VIN**) on JST PH connectors.

### Expansion & Interconnectivity

- **mikroBUS™** Slot: M1 slot for Click® modules, plus **MBL** / **MBR** connectors (not installed by default) to extend the mikroBUS™ bus to other boards.
- **IoTextra** Mezzanines: 12-pin **HOST** connector (HOST-P12 pinout) for connecting IoTextra modules via a cable.
- **I²C** Connector: 4-pin JST PH connector with switchable pull-up resistors.
- **AUX1** / **AUX2**: Auxiliary connectors with the remaining MCU signals.

### On-board Peripherals

- **LM75B** Temperature Sensor on the I²C bus (address selectable by jumpers).

### The IoTextra Ecosystem

The adaptors connect to the **IoTextra** mezzanine series via the **HOST** connector, allowing you to customize your device's I/O:

- **IoTextra Input**: 8-channel isolated digital inputs (up to 36V).
- **IoTextra Relay2**: 4-channel SPDT relay module.
- **IoTextra SSR Small**: 8-channel solid-state relay module.
- **IoTextra MOSFET2**: 8-channel isolated N-channel MOSFET switch module.
- **IoTextra Octal**: 4 isolated digital inputs + 2 NPN outputs + 2 SPST relays.
- **IoTextra Octal2**: 4 isolated inputs + 4 high-power NPN outputs.
- **IoTextra Octal3**: 4 isolated digital inputs + 4 latching DPDT relays.
- **IoTextra Octal4**: 4 isolated digital inputs + 4 SPST relays.
- **IoTextra Analog**: 4-channel 16-bit ADC (ADS1115) for 4-20mA/voltage signals.
- **IoTextra Analog3**: 8-channel differential 12-bit ADC (ADS7828) for 0-5V and 0-20mA/4-20mA signals.
- **IoTextra Combo**: 2 relays + 2 precision analog inputs.

---

## Getting Started

- Choose the adaptor for your MCU development board.
- Install the MCU module and, optionally, a **mikroBUS™** Click® module.
- Connect an **IoTextra** mezzanine to the **HOST** connector via a 12-pin cable (optional).
- Connect power (9-36VDC) and start developing.

---

## Hardware Specifications

Full hardware specifications — including pinouts, jumpers, signal matching tables, PCB layouts and schematics — are located inside the module folders:

- **[Arduino Nano Adaptor](./Arduino%20Nano%20Adaptor/)**
- **[Teensy Adaptor](./Teensy%20Adaptor/)**

Each module directory includes its own documentation in versioned subfolders (e.g., `v.2.21`).

---

## Ordering Information

### 📦 SKU Information

The SKU description of each adaptor is located in its module folder (`SKU.md`).

---

## Licensing

This repository uses separate licenses per asset type:

- **Code:** [`LICENSE_CODE`](./LICENSE_CODE) — MIT License
- **Schematics & Documentation:** [`LICENSE_HARDWARE.md`](./LICENSE_HARDWARE.md) — CC BY-SA 4.0
- **Documentation:** [`LICENSE_DOCS.md`](./LICENSE_DOCS.md)
- **Media:** [`LICENSE_MEDIA.md`](./LICENSE_MEDIA.md)

---

**Developed by MTH LLC** | [makethingshappy.io](http://www.makethingshappy.io)
