# Switch-!t ActivePedalPCB
This is a custom PCB designed for the [DIY Force Feedback Pedal](https://github.com/ChrGri/DIY-Sim-Racing-FFB-Pedal). Similar to the V4 PCB from the previously mentioned repository, it is designed to accommodate all the required development and breakout boards. The PCB is built around the Waveshare [ESP32-S3-DEV-Kit-N8R8](https://www.waveshare.com/wiki/ESP32-S3-DEV-KIT-N8R8) and features only five SMD components that need to be soldered by hand.

It is intended to operate via a single USB-B connector for each pedal, powered by a single Meanwell GST360B36-C6P power supply. The power supply can be daisy-chained from one pedal to another. Additionally, the PCB includes space for an optional N7805 step-down converter, enabling all electronics to be powered directly by the power supply. If you choose to solder the N7805, ensure that the 5V connection from the JST-XH header labeled "USB" to the USB-C plug remains unconnected.

# Soldering you PCB
The PCB is designed to allow sub-boards to be attached using female headers or soldered directly to the board. If you opt for direct soldering, follow these steps:
1. Front Side: Start by soldering the SMD components, then solder the pin headers for the ESP32-S3-DEV-KIT-N8R8.
2. Back Side: Solder the ADS1256 module.
3. Front Side: ESP32-S3-DEV-KIT-N8R8: Attach it to the already soldered headers.
   
Once these steps are complete, you can solder all remaining components to the PCB.
