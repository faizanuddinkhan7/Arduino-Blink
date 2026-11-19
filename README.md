# Arduino-Blink Project

A minimal C++ firmware project for the Arduino Uno managed via the PlatformIO Core CLI.

## Prerequisites

Required system installations:
* **PlatformIO Core (CLI)** (`pio`)
* **Git** 

---

## Setup 

1. Clone the repository and navigate to the project root directory:
   ```bash
   git clone <https://github.com/faizanuddinkhan7/Arduino-Blink.git>
   cd Arduino-Blink
   ```

---

## CLI Workflow Commands

Run these standard PlatformIO commands directly from the system terminal.

### 1. Build Code (Compile)
Compiles the C++ source code:
```bash
pio run
```

### 2. Upload to Arduino Uno
Connect the physical Arduino Uno to the computer via USB:
```bash
pio run --target upload
```

### 3. Open Serial Monitor
Monitor and print messages (`Serial.println`) sent from the Arduino back to the terminal output channel:
```bash
pio device monitor
```
