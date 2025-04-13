# Changelog

## [0.0.1] - 2025-04-13

First release. Only tested on Android (Pixel 9 Pro and Pixel 8 Pro). Firmware
tested on nrf52840dk, nrf52840dongle and xiao nrf52840.

Demo: https://www.youtube.com/shorts/DDajfWiR05o

Stable features:

- Discover and add devices
- Connect, disconnect, remove device
- Auto-reconnect when connection lost
- Give custom name to device (client only)
- Turn switch on/off
- Optional proximity mode (auto on/off based on proximity). Configurable entry/exit time delay
  before switch is toggled.
- View RSSI as seen by device to help configure proximity mode
- Switch modes; latch or momentary with configurable delay
- Enable/disable pairing mode
- Factory reset
