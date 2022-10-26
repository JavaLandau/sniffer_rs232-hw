# Hardware project for Sniffer RS-232
The repository contains Altium Designer project for Sniffer RS-232.  

![](https://github.com/JavaLandau/sniffer_rs232-hw/blob/main/images/main.png?raw=true)

Sniffer RS-232 is RS-232 autodetector & monitor which can recognize UART parameters on TX & RX RS-232 lines  
(baudrate, word length, parity bit) and output monitored data via USB using COM terminal (have been tested on [PuTTY](https://www.putty.org/) and [TeraTerm](https://ttssh2.osdn.jp/index.html.en)).  

The device is designed so to be connected to RS-232 line, passing traffic through itself working as repeater for TX & RX channels.  
It allows Sniffer RS-232 to be transparent for working of target devices which use RS-232. Scheme of normal work of Sniffer RS-232 is on picture below.

![](https://github.com/JavaLandau/sniffer_rs232-hw/blob/main/images/sniffer_rs232.png?raw=true)

It is not compalsory to use Sniffer RS-232 by scheme above, it can be connected to one or both RS-232 lines in parallel for example.  

Despite of the fact that the device is designed to monitor RS-232 data, it also can be useful for LIN monitoring.  
In order to use feature of LIN detection & monitoring it requires to connect hardware LIN interface to Sniffer RS-232 as it done below, for example  

![](https://github.com/JavaLandau/sniffer_rs232-hw/blob/main/images/lin_interface.png?raw=true)

The device is designed to communicate with display [LCD1602A](https://www.openhacks.com/uploadsproductos/eone-1602a1.pdf)

The project is also available in the [PCBWay](https://www.pcbway.com/project/shareproject/Sniffer_RS_232_537dda4e.html)  
The firmware for the project is available in the repository [sniffer_rs232-fw](https://github.com/JavaLandau/sniffer_rs232-fw)