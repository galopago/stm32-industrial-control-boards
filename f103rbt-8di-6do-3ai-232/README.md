# STM32 INDUSTRIAL CONTROL BOARD

Pin mapping for STM32 based industrial control boards advertized as compatible with FX1N, FX2N, FX3U PLC software. Usually enclosed in din rail mountable enclosures.


Upper view                    |Lower view                 
------------------------------|--------------------------
![](/assets/img/upper.jpg)    |![](/assets/img/side.jpg) 


Board Upper view              |Board Lower view                 
------------------------------|--------------------------
![](/assets/img/upper.jpg)    |![](/assets/img/side.jpg) 


## Features

| FEATURE         | VALUE 
|-----------------|--------------
| Processor       | STM32F103RBT
| Power Input     | 24 VDC
| Digital Inputs  | 8 optically isolated
| Digital Ouptuts | 6 relay
| Analog inputs   | 3
| Serial port     | RS232



This boards are usually equipped with relay outputs, opticaly isolated digital inputs, RS232 serial port, 24VDC input power. Are enclosed in a convenient plastic din rail compatible mount enclosure, and screw terminals for input/outpus. This is a collective effort to document pinmaps for most common types of board available on online markets, so they will be usable with different firmware and build tools, like arduino.

## Versions

There are several board versions, each one with different personalities


| PROCESSOR    | DI | DO | AI | A0 | SERIAL PORT |VISIBLE PCB MARK| LINK
|--------------|----|----|----|----|-------------|----------------|---------------------------------------------------
| STM32F103RBT | 8  | 6  | 3  | 0  |   RS232     | NONE           |[f103rbt-8di-6do-3ai-232](/f103rbt-8di-6do-3ai-232)  
