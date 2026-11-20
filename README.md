# RFID Tarot Cards — BYU TEC 2027

A group project for an escape room created for the **BYU Themed Entertainment Club**. The project uses RFID-RC522 readers to detect tarot cards and support an interactive escape-room experience.

## Project Status

In development.

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for notable changes to the project.

## Hardware

- Arduino-compatible board — **[add board model]**
- RFID-RC522 reader(s) — **[add quantity]**
- Tarot cards with compatible RFID tags
- **[Add other hardware, such as LEDs, displays, or audio components]**

## Software

- [PlatformIO](https://platformio.org/)
- Arduino framework
- **[Add required libraries]**

## Getting Started

### 1. Install PlatformIO

Install [Visual Studio Code](https://code.visualstudio.com/) and the [PlatformIO IDE extension](https://platformio.org/install/ide?install=vscode), or install the PlatformIO Core CLI.

### 2. Clone the Repository

```bash
git clone https://github.com/mscoresby3/rfid-tarot-cards-BYU-TEC-2027.git
cd rfid-tarot-cards-BYU-TEC-2027
```

### 3. Configure the Project

Open the project folder in PlatformIO.

Configure `platformio.ini` with the appropriate board, Arduino framework, and required libraries. Update the firmware with the pin assignments for the RFID readers and any other connected components.

### 4. Build the Firmware

```bash
pio run
```

### 5. Upload the Firmware

Connect the board to your computer, then run:

```bash
pio run --target upload
```

### 6. Open the Serial Monitor

```bash
pio device monitor
```

Set the monitor speed in `platformio.ini` to match the baud rate used by the firmware.

## Wiring

**[Add a wiring diagram or pin assignment table once the board and reader configuration are finalized.]**

## Usage

**[Describe the escape-room interaction, including which cards players scan, whether card order or placement matters, and what happens when the puzzle is solved.]**

## Planned Repository Structure

```text
.
├── include/       # Project header files
├── lib/           # Project-specific libraries
├── src/           # Arduino firmware source
├── test/          # PlatformIO tests
└── platformio.ini # PlatformIO project configuration
```

## Team

**BYU Themed Entertainment Club — 2027 Project Team**

- **[Add team members and roles]**
