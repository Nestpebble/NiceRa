# NiceRa
My DIY boards.

![Nice-ra sidekicks and a promicro ](./nicera-sidekicks.png)

## Disclaimer
These boards have not been tested under every circumstance and may have bugs. Manufacture at your own risk!

## Notes
[Standard pinout for Pro-Micro board](./Pro-micro_std_pinout.md)

[Lora modules & dimensions](./Lora_Modules.md)

[GPS power consumption measurements](./GPS_power_consumption.md)

## Useful links:
### [Haruki Toreda stuff](https://harukitoreda.github.io/Meshtastic-Experiments/)

## Other peoples boards:
### Fake-tec - NRF52840
https://github.com/gargomoma/fakeTec_pcb/
* Uses the same NRF52840 Pro-micro boards as my designs above
* An excellent design, using the outline of the Heltec v3 to take advantage of all the cases out there.
* Has a voltage divider built-in, with thru-hole or SMD resistors
* Can flush-mount the PCB to reduce height even further

### Cheapmesh - ESP32-C3
https://gitlab.com/paulhausk/CheapMesh/-/tree/main
* HT-CT62 based
* Multiple options to power & interface
* Initial issue has native USB d+/d- switched - check before building
* Has components on the underside that make it harder to assemble

### Econotastic - RP2040
https://sites.google.com/view/econotastic/home
* RP Pico (or clone) as MCU
* Uses RA-01SH, but can also use HT-RA62
* Changes in code not really required - see `TCXO_OPTIONAL`

### Mesh Heltec Tiny - ESP32-C3
https://oshwlab.com/vardas/meshheltectiny
* HT-CT62 based
* Pretty complete


