# PsahkoESP32 Firmware Repository

This repository contains compiled firmware binaries for the PsahkoESP32 project.

## Latest Version: 1.0.2

### Download Links
- **[firmware_v1.0.2.bin](firmware_v1.0.2.bin)** - Version 1.0.2
- **[latest.bin](latest.bin)** - Always points to latest version

### OTA Update Support
This firmware supports Over-The-Air updates. When your device is connected to WiFi:
1. Access the web interface (device IP address)
2. Go to the "OTA Update" section
3. Click "Check for updates"
4. Click "Install update" if available

### Verification
```
MD5: 42c3e9fcdb2876e1b9ac5db6622d9d11
SHA256: a9ba65d9a83873ef41e731dfbdd6f17020c37e356ca830bfbf9eef580f03fbd1
```

### How to Flash
1. Download the firmware file
2. Use [esptool.py](https://github.com/espressif/esptool) or ESP32 Flash Download Tool
3. Set flash mode: QIO, Flash size: 4MB, Flash freq: 80MHz
4. Upload at address 0x10000

### Available Versions
- [v1.0.2](firmware_v1.0.2.bin)
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
https://raw.githubusercontent.com/oh2fxd/PsahkoESP32-FW/main/firmware_v1.0.2.bin
```

*Last updated: 2025-12-03 12:37:34*
