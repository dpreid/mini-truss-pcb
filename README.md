## Mini Truss PCB design

# Current state

An Arduino Nano 33 IoT is used as the microcontroller for the lab. Firmware, in an unfinished state, is available [here](https://github.com/dpreid/truss-firmware/tree/main/MiniTruss). However, this remains in a hybrid state between the old prototype truss with servo load control and the new mini-truss that runs from a single arduino and has a linear actuator for load control.

The PCB design currently consists of the analogue-to-digital converters (ADC) for strain gauge measurements and the Arduino Nano 33 IoT. The ADC uses the [HX711](https://github.com/dpreid/mini-truss-pcb/blob/main/docs/hx711_english.pdf)

# TODO

- Check correct resistance values are being used for voltage divider within ADC unit (R1 and R2 and then equivalents).
- Firmware and PCB updates for the new [linear actuator](https://github.com/dpreid/mini-truss-pcb/blob/main/docs/Actuonix%2BL16%2BDatasheet.pdf)
- TBC, whether we will stick with the Arduino Nano 33 IoT or convert to using Tim Drysdale's custom [microcontroller board](https://github.com/timdrysdale/atmega-demo)
- testing with prototype mini truss once strain gauges are ordered.
