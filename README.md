# Shark Sense Android

WiFi/BLE radar app with device-relative orientation plotting, retro cyberpunk UI, targeting mode, and optional map overlay.

## Features (planned)
- Separate WiFi and BLE scan modes
- Polar radar with real device heading (magnetometer + IMU)
- Pinch-to-zoom radar
- Traditional green-on-black radar view
- GPS + semi-transparent map overlay mode (local image zoom)
- Target mode: select AP/device → green arrow + proximity beeps
- Permission checks on startup
- WiFi scan throttling detection + developer options guidance
- Precision-focused, responsive UI

## Requirements
- Android Studio (latest)
- Device with WiFi, BLE, accelerometer, and magnetometer
- Location permission (required by Android for WiFi scans)
- Developer options → Wi-Fi scan throttling = OFF for higher scan rates

## Build
1. Clone this repo
2. Open in Android Studio
3. Sync Gradle
4. Run on device (emulator has limited sensor support)

This is the Android companion to the M5Shark / AtomS3R field tool project.
