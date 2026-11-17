# ESP32 Keyboard: Bluetooth control page

A web page that controls an ESP32-S3 acting as a USB keyboard. The page talks to the ESP32 over
**Bluetooth LE** (Web Bluetooth), and the ESP32 types on whatever computer its USB port is plugged into.

**Open:** https://reetamdan.github.io/esp32-ble-keyboard/

- **Browsers:** Chrome or Edge on Android, Windows, macOS and ChromeOS. On iPhone/iPad, use the Bluefy browser. Firefox and Safari don't support Web Bluetooth.
- **First connection:** the phone asks to pair. Enter the 6-digit PIN set on the ESP32.
- **Install:** in Chrome, use "Install app" or "Add to Home screen". The page then works offline.

This repository contains only the static page: no passwords, PINs or device identifiers.
Access control is Bluetooth pairing with the PIN (LE Secure Connections, authenticated and bonded).
