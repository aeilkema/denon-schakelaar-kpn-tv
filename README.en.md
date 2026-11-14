# Denon Schakelaar

[Nederlands](README.md) | **English**

Denon Schakelaar is an Android TV app for controlling a Denon AVR-X2400H from a KPN TV+ Box. It discovers the receiver on the local network and provides controls to power it on and select an HDMI input.

Settings let you change device names, HDMI numbers, icons and input order. Inputs can be hidden from the home screen. The interface is designed for remote control navigation and uses a dark theme.

## Installation

Download [`outputs/DenonSchakelaar.apk`](outputs/DenonSchakelaar.apk) and install it on an Android TV device. Sideloading is required; the app is not available from the Play Store. The receiver and Android TV device must be on the same local network.

## Operation and limitations

- Receiver discovery uses SSDP on the local network.
- Power and input selection use Denon Telnet commands on port 23.
- HDMI numbers start with the AVR-X2400H factory assignments. Change them if your receiver uses a different configuration.
- The app does not read custom source names or HDMI assignments from the receiver. Configure them in the app.
- Waking a connected device depends on HDMI-CEC and that device’s settings. Some devices, including the Nintendo Switch, may need to be woken manually.
- The app was made for the Denon AVR-X2400H. Other Denon and Marantz models have not been tested.

## Personal use

This project is published for personal use. No support or warranty is provided. No license is granted for reuse, redistribution or commercial use without the author’s permission.
