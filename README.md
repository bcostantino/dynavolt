# DynaVolt
### Power Control Unit (PCU) | PMIC

DynaVolt controls the open/closed state of several high-voltage (12 - 48 V) MOSFET power switches and drives variable power to several independent buses.

---

#### IS-100
**In Development**: 05.10.23

- 2 HV DC inputs, 1-bit digital control signal
- sources current to 2 individual power buses (A and B) at up to 24W (≤ 2A @ 12V<sub>DC</sub>) each
- bus voltages are configurable to: 3.3V, 5V or 12V
- powered by 12 - 48 V DC PSU or batteries

---

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
