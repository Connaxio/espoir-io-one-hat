# IO One mikroShield
The IO One mikroShield is a multi-purpose mikroBUS<sup>TM</sup> add-on board. It features nine signal-voltage-ground (SVG) headers for servomotors, a Digilent Pmod<sup>TM</sup> Compatible I<sup>2</sup>C connector and a SHTC3 temperature and humidity sensor.

## Features
- 3x input-only analog/digital SVG headers
  - Jumper-selectable voltage (3.3 V or 5 V)
  - Single on/off PMOS switch for all three voltage pins
  - 2 of the signals require the optional 3-pin header to be soldered to the add-on board and connected to the mikroBUS<sup>TM</sup> mainboard. These pins are compatible with Connaxio's [Espoir](https://github.com/Connaxio/espoir). The voltage pin for these headers can still be used as a digital output without the extension header.
- 3x input-output, analog-digital SVG headers
  - Jumper-selectable voltage (3.3 V or 5 V)
  - Single on/off PMOS switch for all three voltage pins
- 3x 1-wire SVG headers
  - Fixed 3.3V voltage
  - Controllable via UART or bit-banging
- 1x Digilent Pmod<sup>TM</sup> Compatible I<sup>2</sup>C connector
  - Jumper-selectable voltage (3.3 V or 5 V)
  - Includes RST and INT pins for extended usage
  - Also convenient for connecting various hobby breakout boards with breadboard jumper wires.
- SHTC3 I<sup>2</sup>C temperature and humidity sensor
  - 0.2 <sup>o</sup>C temperature accuracy from -40 <sup>o</sup>C to +125 <sup>o</sup>C
  - 2 % humidity accuracy
