# STM32H7-based_Custom_Board
This is an STM32H7-based MCU board designed and developed in Altium Designer.

For this design, the Schematic is divided into two sections namely: **MCU and Other parts.** The MCU section holds the STM32H743VIT6 module with its various input/output peripherals as well as its power circuitry.

![MCU](https://user-images.githubusercontent.com/103453226/231606481-93c435fa-3624-40eb-b58f-866d66131d48.png "MCU Schematic")

On the other hand, the Other parts section houses several connectors including a debug connector and an SPI camera module connector as well as an SD Card module for data storage.

![Other Parts](https://user-images.githubusercontent.com/103453226/231606534-4982a634-a5b5-4620-abfa-f10b1c932753.png "Other Parts Schematic")

For the actual PCB section, the board is a 2-layer board with the design rules and layer stack tailor made to accomodate JLCPCB manufacturing capabilities. More on their manufacturing and assembly capabilities can be found [here](https://jlcpcb.com/capabilities/pcb-capabilities).

The final PCB looks like this

![PCB](https://user-images.githubusercontent.com/103453226/231608764-7cbc11a1-1a54-4b34-b5c9-71818795da05.png "PCB Final Layout")