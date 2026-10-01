Hi everyone,

I'm currently designing a custom PCB for a four-wheel load measurement system for motorsport applications.

Each PCB is intended to be installed on one wheel and includes:

- 1S Li-ion battery
- TP4056 Li-ion charger
- Automatic battery/external power selection
- Reverse-polarity protection
- TPS63070RNMR buck-boost converter
- Arduino Nano ESP32
- HX711 load-cell ADC
- Single load cell input

I've attached the current schematic.

I would really appreciate it if someone with experience in power electronics, battery charging, ESP32 hardware or load-cell instrumentation could take a look at the design and point out any potential mistakes or improvements.

In particular, I would like feedback on:

1. The TP4056 charging and NTC temperature-monitoring circuit.
2. The P-MOSFET power-path and reverse-polarity protection.
3. The TPS63070RNMR 7 V buck-boost stage.
4. The power supply and connections between the Arduino Nano ESP32 and HX711.
5. Any component, protection or layout considerations that I may have overlooked.

This is still a provisional schematic, so I'm mainly looking for a technical review before moving on to PCB layout and manufacturing.

Thanks in advance for taking the time to have a look!
