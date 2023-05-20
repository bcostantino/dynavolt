# DynaVolt
### Power Control Unit (PCU) | PMIC

DynaVolt controls the open/closed state of several high-voltage power switches and drives variable power to several independent buses.

---

#### DV-100
**In Development**: 05.10.23

- 2x 12 - 36 V<sub>DC</sub> supply inputs (1-bit digital select) w/ lock and enable
- sources current to 2 individual power buses (A and B) at up to 24W (≤ 2A @ 12V<sub>DC</sub>) each
- bus voltages are configurable to: 3.3V, 5V or 12V

---

### Parts

- [TI - TPSM63603 - High-density, 3-V to 36-V input, 1-V to 16-V output, 3-A power module](https://www.ti.com/product/TPSM63603)



### Contribution

- **To use `~/spice` files with LTSpice** (see [LTspice: Simple Steps to Import Third-Party Models](https://www.analog.com/en/technical-articles/ltspice-simple-steps-to-import-third-party-models.html))

    Add the necessary path(s) (from `<REPO_DIRECTORY>/spice/lib/`) to the **Symbol Search Path** and **Library Search Path** in **Tools** > **Control Panel** > **Sym. & Lib. Search Paths**. *Note: Generally, `.asc` and `.asy` files coorespond to symbols and `.spi` to libraries*.


### License

Copyright © 2023 Brian Costantino

DynaVolt is a free hardware design: you can redistribute it and/or modify it under the terms of the CERN Open Hardware License (OHL) v2.

DynaVolt is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See `~/LICENSE` for more details.

You should have received a copy of the CERN-OHL-W v2 along with this repository. If not, see [ohwr.org/cern_ohl_w_v2.txt](https://ohwr.org/cern_ohl_w_v2.txt).



### References

- [Gammon Forum - MOSFET switches](https://www.gammon.com.au/motors)
- [ADI, LTspice, How can to simulate a NTC thermistor?](https://ez.analog.com/design-tools-and-calculators/ltspice/f/q-a/546803/how-can-to-simulate-a-ntc-thermistor)
