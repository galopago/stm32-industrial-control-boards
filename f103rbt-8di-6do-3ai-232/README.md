# STM32 INDUSTRIAL CONTROL BOARD

Pin mapping for STM32 based industrial control boards advertised as compatible with FX1N, FX2N, FX3U PLC software. Usually encased in din rail mountable enclosures.

## F103RBT-8DI-6DO-3AI-232

|Top view                      |Bottom view                 
|------------------------------|--------------------------
|![](assets/img/upper.jpg)     |![](assets/img/lower.jpg) 


|Board top view                |Board bottom view                 
|------------------------------|--------------------------
|![](assets/img/upperboard.jpg)|![](assets/img/lowerboard.jpg) 

|Processor part number       |
|----------------------------|
|![](assets/img/procpart.png)|


## Features

| FEATURE         | VALUE 
|-----------------|--------------
| Processor       | STM32F103RBT
| Power Input     | 24 VDC
| Digital Inputs  | 8 optically isolated
| Digital Ouptuts | 6 relay
| Analog inputs   | 3 non isolated, resistor divisor 15K/30K
| Serial port     | RS232

## Pinout

| BOARD FUNCTION  | PROCESSOR PIN 
|-----------------|---------------
| RUN LED         | PB12
| ERROR LED       | PB13
| RS232 TX        | PA9
| RS232 RX        | PA10
| RUN/STOP SWITCH | PC9
| X0              | PA0
| X1              | PA1
| X2              | PB9
| X3              | PA6
| X4              | PA7
| X5              | PB5
| X6              | PB4
| X7              | PD2
| Y0              | PB8
| Y1              | PB1
| Y2              | PB10
| Y3              | PB0
| Y4              | PC5
| Y5              | PC4
| AD1      		  | PC1
| AD2      		  | PC2
| AD3      		  | PC0



| 4 pin header  |
|---------------|
| 3.3V          |  
| PC11          |
| PC10          | 
| GND           |
