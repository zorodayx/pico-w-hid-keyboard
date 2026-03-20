
# Introduction


- Raspberry Pi Pico is a small and powerful micro controller board. 
- Micro controllers are kind of small and specialized computer that we can program to complete a specific task we need .

## Pico Variants 


| Pico                                                                                                                                                         | Pico W                                                                                                                                | Pico H                                                                                                                                                              | Pico WH                                                                                                          |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| This is the regular "base mode" pico . All Pico variants run the same processor , RAM and memory as this version . other versions add things to this variant | This model comes with wirless capabilities allowing you to connect it to the internet through wifi , and allows you to use Bluetooth. | This also is the same as the regular Pico , however it comes with pins headers already attached to the board. good option if you don't want to put your own headers | this is identical to Pico W , including wireless capabilities , it just have the headers also like the H variant |
| ![[Screenshot from 2026-03-19 23-07-49.png\|1000]]                                                                                                           | ![[Screenshot from 2026-03-19 23-08-05.png\|1000]]                                                                                    | ![[Screenshot from 2026-03-19 23-07-59.png]]                                                                                                                        | ![[Screenshot from 2026-03-19 23-08-11.png]]                                                                     |
> For more Info and detailed features : [Raspberry Pi](https://www.raspberrypi.com/documentation/microcontrollers/pico-series.html)


# 2. GPIO pins and Wireless Board Layout 

the General Purpose Input/Output pins on Pico are numbered in two ways 

![[Screenshot from 2026-03-19 23-21-24.png]]


- GPIO pins can be numbered numerically or by function like GP1 , GP2  , ...etc. 



# 3. Communication Protocols 

## 3.1 UART
- Universal Asynchronize Receive/Transmit 
- Baud Rate (how fast they communicate)
## 3.2 SPI 
- serial peripheral interface
- have four wires and enable more than 2 devices talking at the same time on the same pins 
- connect to another device with different logic 
- Controller target (master-slave architecture) (Primary-Secondry)(Controller-worker)(Initiator-Responder)
- 