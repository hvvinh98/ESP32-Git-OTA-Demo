# ESP32-Git-OTA-Demo

Static firmware and manifest repository for testing the ESP32 OTA demo.

- `manifest.json` publishes the version and ELF SHA-256 for each hardware target.
- `firmwares/ESP32WROOM32.bin` is the matching ESP32-WROOM-32 firmware image.

The checked-in image is version `3.1.1`, built from the matching ELF. Publish
the manifest and firmware together; do not update one without the other.
