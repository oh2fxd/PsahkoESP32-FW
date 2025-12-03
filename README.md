# PsahkoESP32 Firmware Repository

This repository contains compiled firmware binaries for the PsahkoESP32 project.

## Latest Version: 1.0.1

### Download Links
- **[firmware_v1.0.1.bin](firmware_v1.0.1.bin)** - Version 1.0.1
- **[latest.bin](latest.bin)** - Always points to latest version

### OTA Update Support
This firmware supports Over-The-Air updates. When your device is connected to WiFi:
1. Access the web interface (device IP address)
2. Go to the "OTA Update" section
3. Click "Check for updates"
4. Click "Install update" if available

### Verification
```
MD5: 8f91c6fd3f753080911d9f50e78df338
SHA256: 1dbb395c9ffdb69bff215c3f6808b97a001ee482097a2559bb0631efe5e2998c
```

### How to Flash
1. Download the firmware file
2. Use [esptool.py](https://github.com/espressif/esptool) or ESP32 Flash Download Tool
3. Set flash mode: QIO, Flash size: 4MB, Flash freq: 80MHz
4. Upload at address 0x10000

### Available Versions
- [v1.0.1](firmware_v1.0.1.bin)
- [v1.0.0](firmware_v1.0.0.bin)

### Source Code
Source code is maintained in a private repository.

### Auto-update URL for ESP32 OTA
```
https://raw.githubusercontent.com/oh2fxd/PsahkoESP32-FW/main/latest.bin
https://raw.githubusercontent.com/oh2fxd/PsahkoESP32-FW/main/version.txt
```

For specific version:
```
https://raw.githubusercontent.com/oh2fxd/PsahkoESP32-FW/main/firmware_v1.0.1.bin
```

*Last updated: 2025-12-03 11:42:03*
