# Nitrox Analyser and Trimix Analyser Connector

This public repository provides signed over-the-air firmware files for two independent DIY diving projects published by FiddlerCrab UG (haftungsbeschränkt). The product websites are the authoritative source for browser installation, hardware compatibility, build instructions, manuals, pricing, and safety notices.

## DIY Nitrox Analyser

Build a compact LilyGo T-Display S3 oxygen analyser with an ADS1115, galvanic O2 cell, MOD calculation, a local Web UI, and Bluetooth labels for Niimbot B1/B21 printers.

- [Nitrox Analyser project](https://www.nitroxanalyser.com/)
- [ESP32-S3 Nitrox Analyser build and ADS1115 wiring guide](https://www.nitroxanalyser.com/nitrox-analyser-build-guide)
- [Nitrox Analyser HTML manual](https://www.nitroxanalyser.com/nitrox-analyser-manual)
- [Calibration and verification guide](https://www.nitroxanalyser.com/nitrox-analyser-calibration)
- [Troubleshooting guide](https://www.nitroxanalyser.com/nitrox-analyser-troubleshooting)
- [Direct browser firmware installer](https://www.nitroxanalyser.com/install?target=nitrox)

## Divesoft Trimix Analyser Connector

Build a receive-only ESP32-S3-Zero-compatible adapter that reads the documented Divesoft He/O2 analyser output and prints checked oxygen/helium cylinder labels on a portable Niimbot printer. Basic Nitrox labels are free; Trimix labels are available through the optional Pro licence.

- [Trimix Analyser Connector project](https://www.trimixanalyser.com/trimix)
- [Divesoft analyser ESP32 adapter build guide and pinout](https://www.trimixanalyser.com/trimix-analyser-build-guide)
- [Trimix Analyser Connector HTML manual](https://www.trimixanalyser.com/trimix-analyser-manual)
- [Divesoft data-output to ESP32 guide](https://www.trimixanalyser.com/divesoft-data-output-esp32-adapter)
- [How to print Trimix cylinder labels](https://www.trimixanalyser.com/trimix-cylinder-labels)
- [Troubleshooting guide](https://www.trimixanalyser.com/trimix-analyser-troubleshooting)
- [Direct browser firmware installer](https://www.trimixanalyser.com/install?target=divesoft)

## Installation

Use the browser installers linked above in desktop Chrome or Edge. They validate the ESP32-S3 family and provide separate full-install and settings-preserving update paths. Do not flash the raw binary files directly unless you understand the signed release and partition layout.

For the Trimix connector, disconnect the adapter completely from the Divesoft analyser before attaching USB or flashing firmware.

## Safety

These are DIY devices and documentation, not finished certified commercial analysers. Independently verify analyser readings and every printed cylinder label before diving. Follow the current manufacturer instructions for the oxygen cell, reference analyser, printer, battery, and Divesoft analyser.

Support: [hello@nitroxanalyser.com](mailto:hello@nitroxanalyser.com) or [hello@trimixanalyser.com](mailto:hello@trimixanalyser.com)
