# Ctrl M Controller for Model M

![ctrl-m](https://brain4free.org/wiki/lib/exe/fetch.php/elektronik:modelm:img_20221218_200726.jpg)


This is a replacement controller for the famous IBM Model M keyboard based on the STM32F072 microcontroller. Goal is to get it upstream in QMK.

Work in progress, prototypes are working in Model M from 1989, there is a bug for the version from 1986 and test for other variants are outstanding.

## Hardware

Controller based on a STM32F072 chip and designed with KiCAD.

To make the controller as flexible as possible there are four possible LED and earth cable connectors. Also the PCB can be cut into a smaller variant that fits the later IBM/Lexmark variant.

The four LED connector variants are:

    J8 is a 12 pin connector is mounted for J8 for both LED and keyboard
    J8 is a 8 pin connector and J9 is a 4 pin connector
    J8 is a 8 pin connector and J12 is a 4 pin connector
    J8 is a 8 pin connector and J10 is a 4 pin header

https://github.com/nuess0r/ctrl-M

To fill the gab between the USB connector and the case and also to make it easier to press the bootloader button a small plastic part (button_lever.amf) was designed with FreeCAD that can be 3D printed.

## Software

https://github.com/nuess0r/qmk_firmware/tree/ctrl_m/keyboards/ctrl_m

## Assembly Instructions

https://brain4free.org/wiki/doku.php/elektronik:ctrl_m#assembly_instructions
