# USB-3.1-to-SATA-6Gbps
USB 3.2 gen 2 (SuperSpeed+ 10Gbps) to SATA 6Gbps

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
- W25Q16BVSSIG 16Mbit SPI Flash  Memory
- 1.5uH/2.2uH Inductor
- Power/Busy LEDs

## PCB 
This board uses a 4 layer stackup with a  1.6mm thickness:

- POWER/SIGNAL

- GND
  
- GND
  
- POWER/SIGNAL

High Speed diferential lines need a refrence ground plane so internal planes are ground referance planes for the High speed USB lines

The Pcb was inspired by similar boards that use VL711/VL715 Ics. The capacitors are standard values that are use as decoupling capacitors.


### Schematic:
![Schematic](/USB%203.0%20to%20Sata.pdf)

## PCB Screenshots

![usb3satafront](pcb%20pics/front.png)
![usb3sataback](pcb%20pics/back.png)
![usb3satafront3d](pcb%20pics/front3d.png)
![usb3sataback3d](pcb%20pics/back3d.png)



