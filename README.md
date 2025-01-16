# USB-3.1-to-SATA-6Gbps
USB 3.1(10Gbps, SuperSpeed 10Gbps, [USB 3.2 gen 2](https://external-preview.redd.it/aEU8RJTeqexdNhj47QB3PRV0-shMQXoTVqeNHO9yYpo.png?auto=webp&s=28028ef6d0fd850dfabad659cbfcc59d81c76829)) to SATA 6Gbps

This Board is based on the VIA Labs VL716 

## VL716

- High performance, low power single chip USB 3.1 to SATA 6Gb/s bridge controller 
- USB Type-C connector support
###  Built-in Voltage Regulators

- 5.0V to 3.3V LDO

- 5.0V to 1.2V switching DC-DC

## Other Parts 

- USB C 24P Connector (THT inside pins)
- 25Mhz Crystal for Ic
- Sata 22P horizontal female SMD connector
- PM25LD512  512KB SPI Flash  Memory
- ?uH Inductor (Value TBA)
- Power/Busy LEDs

## PCB 
This board uses a 4 layer stackup with a  1.6mm thickness:

- POWER/SIGNAL

- GND
  
- GND
  
- POWER/SIGNAL

High Speed diferential lines need a refrence ground plane so internal planes are ground referance planes for the High speed USB lines

The Pcb was inspired by similar boards that use VL711/VL715 Ics. The capacitors are standard values that are use as decoupling capacitors.

THE DESIGN IS NOT FINAL! KNOW PROBLEMS:

- Abias Resistor value to be determined, used value of ASM1153E/ASM1053E family of ic until i can get my hands on a board that has an VL ic.

- Inductor Value to be determined

Diferential Pairs Impedance:

- SuperSpeed Pairs Impedance: ~90 Ohm

- Sata Pairs Impedance: ~90 Ohm (Spec is 100 Ohms, pcb needs to be modified)

### Schematic:
![USB 3 0 to Sata](https://github.com/user-attachments/assets/0a3b7262-3c18-47a7-9b1f-60b850fa37d3)

## PCB Screenshots

![usb3satafront](https://github.com/user-attachments/assets/e87a4e91-a3c0-4c74-8f43-9853ea00af32)
![usb3sataback](https://github.com/user-attachments/assets/7e04f5d1-69bf-40e7-87a1-89096c32aa60)
![usb3satafront3d](https://github.com/user-attachments/assets/a9bde4d8-fc9b-4837-9eaa-50a20a133ebf)
![usb3sataback3d](https://github.com/user-attachments/assets/3d53e79f-70f6-4c91-b8d8-962831fdac90)


To Do: CC lines, Abias Resistor, Impedance, Inductor Value
