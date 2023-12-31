# Boostlet!

![Boostlet! board 3d view front and back](https://github.com/RobotGrrl/boostlet/blob/main/boostlet_splash.jpg?raw=true)


Embeddable circuit board to boost battery input to 5V intended for small robots. Useful access is provided to two logic level convertors for Neopixels, and a 3.3V regulator. Input and output are protected with PTCs, with the option to not populate with a solder jumper. Castellated connectors enable this circuit board to be added either surface mount or with through-hole 0.1" headers. 

---

## Tech Specs

- V_IN: 0.9 - 4.75V
- V_OUT: 5V, 3A
- V_REG: 3.3V, 1A

### Connectors

J1
- VCC
- NEO_IN2
- NEO_OUT2
- BATT_SIG
- NEO_IN1
- NEO-OUT1
- GND

J2 (Input)
- V_IN (V_BATT)
- GND
- VCC

J3 (Output)
- V_OUT (5V)
- GND
- V_REG (3.3V)

### Solder Jumpers
- JP1: Bypass input PTC
- JP2: Enable 3.3V reg powered from 5V boost output
- JP3: Bypass output PTC
- JP4: Connect 3.3V reg output to Vcc _(be sure Vcc isn't connected to anything!)_
_Solder jumpers are open by default, add solder to connect the pads to close them_

---

## License

Boostlet! (C) Copyright Erin RobotZwrrl, Robot Missions Inc.

12-30-23 v1.0

[RobotZwrrl.xyz/boostlet](http://RobotZwrrl.xyz/boostlet)

[RobotMissions.org](https://RobotMissions.org)


This hardware is released under:

CERN Open Hardware License Version 2.0 - Permissive (CERN-OHL-P)

[https://cern-ohl.web.cern.ch/](https://cern-ohl.web.cern.ch/)


Disclaimer: Distributed as is. No warranty is given. Not responsible or liable for any damage or harm that result from this product.
