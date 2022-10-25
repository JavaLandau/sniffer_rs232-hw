# Hardware project for Sniffer RS-232
The repository contains Altium Designer project for Sniffer RS-232.  

![](https://github.com/JavaLandau/sniffer_rs232-hw/blob/main/images/main.png?raw=true)

Sniffer RS-232 is RS-232 autodetector & monitor which can recognize UART parameters on TX & RX RS-232 lines  
(baudrate, word length, parity bit) and output monitored data via USB using COM terminal (have been tested on [PuTTY](https://www.putty.org/) and [TeraTerm](https://ttssh2.osdn.jp/index.html.en)).

Despite of the fact that the device is designed to monitor RS-232 data, it also can be useful for LIN monitoring.  
In order to use feature of LIN detection & monitoring it requires to connect hardware LIN interface to Sniffer RS-232 as it done below, for example  

![](https://github.com/JavaLandau/sniffer_rs232-hw/blob/main/images/lin_interface.png?raw=true)

The device is designed to communicate with display [LCD1602A](https://www.openhacks.com/uploadsproductos/eone-1602a1.pdf)

The project is also available in the [PCBWay](https://www.pcbway.com/project/shareproject/Sniffer_RS_232_537dda4e.html)  
The firmware for the project is available in the repository [sniffer_rs232-fw](https://github.com/JavaLandau/sniffer_rs232-fw)