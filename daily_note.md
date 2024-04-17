# Daily note
## 15/04/2024
### Microcontroller boards we need to support
[MSP432P401R LaunchPad from Texas Instruments](https://software-dl.ti.com/msp430/msp430_public_sw/mcu/msp430/SIMPLELINK_MSP432_SDK/1.20.00.45/exports/docs/simplelink_mcu_sdk/project0/project0/docs/MSP-EXP432P401R.html)

[MSP432E401Y LaunchPad from Texas Instruments](https://www.ti.com/tool/MSP-EXP432E401Y)

[TM4C129E LaunchPad from Texas Instruments](https://www.ti.com/tool/EK-TM4C129EXL)

[STM32F407G-DISC1 from STM](https://www.digikey.es/es/products/detail/stmicroelectronics/STM32F407G-DISC1/5824404)

[STM32L476RG Nucleo from STM](https://www.st.com/en/evaluation-tools/nucleo-l476rg.html)

### Microcontroller boards we'd like to support (optionally)
[CC3220SF LaunchPad from Texas Instruments](https://www.ti.com/tool/CC3220SF-LAUNCHXL)

[MSP430FR5994 LaunchPad from Texas Instruments](https://www.ti.com/tool/MSP-EXP430FR5994)

[ESP32-C6 DevKit from Expressif](https://www.mouser.es/ProductDetail/Espressif-Systems/ESP32-C6-DevKitC-1-N8?qs=8Wlm6%252BaMh8TjnOR8RwmaBw%3D%3D&mgh=1&vip=1&utm_id=19105062713&gad_source=1&gclid=CjwKCAjww_iwBhApEiwAuG6ccL-T_OCe5tMvoHe6_qJgbdB7G4ubsO1zwnKDqwUsUrsUlbqtqguAuRoCicEQAvD_BwE)

### Sensor/actuator boards we need to support
[BOOSTXL-EDUMKII from Texas Instruments](https://www.ti.com/tool/BOOSTXL-EDUMKII?DCMP=epd-mcu-lyd-tutorial-wwe&HQS=epd-mcu-lyd-tutorial-lydesign-20151008-tf-edbp-wwe)

### Sensor/actuator boards we'd like to support (optionally)

## 16/04/2024
Today we have three options available to us :

- The first would be to create a large main board and other small boards where the microcontroller boards would be placed on top of them, and the small boards would be placed on the large main board.
- The second option would be to install connectors and switches on the main board that would allow for adapting the inputs and outputs of the connectors according to the microcontroller boards.
- The third option would be to directly install many connectors on the main board for the various microcontroller boards.

For the second option : We need to check on each microcontroller boards their types of connections to see which ones are the same in order to use as few switchs as possible.

## 17/04/2024
### MSP432P401R LaunchPad Pinout
![MSP432P401R LaunchPad Pinout](https://software-dl.ti.com/msp430/msp430_public_sw/mcu/msp430/SIMPLELINK_MSP432_SDK/1.20.00.45/exports/docs/simplelink_mcu_sdk/project0/_images/432LP_pinout.png "MSP432P401R LaunchPad Pinout")
### MSP432E401Y LaunchPad Pinout
![MSP432E401Y LaunchPad pinout](https://energia.nu/pinmaps/img/MSP-EXP432E401Y.jpg "MSP432E401Y LaunchPad pinout")
### TM4C129E LaunchPad Pinout
![TM4C129E LaunchPad Pinout](image.png "TM4C129E LaunchPad Pinout")
### STM32F407G-DISC1 Pinout
![STM32F407G-DISC1 Pinout](https://snapeda.s3.amazonaws.com/partimage/STMicroelectronics/STM32F407G-DISC1-Symbol.png "STM32F407G-DISC1 Pinout")
### STM32L476RG Nucleo Pinout
![STM32L476RG Nucleo Pinout](image-1.png "STM32L476RG Nucleo Pinout")
### BOOSTXL-EDUMKII Pinout
![BOOSTXL-EDUMKII Pinout](image-2.png "BOOSTXL-EDUMKII Pinout")

### Tableau
| Microcontroller Boards | Pinout |
| :--------------------: | :----: |
| MSP432P401R LaunchPad  |        |
| MSP432E401Y LaunchPad  |        |
| TM4C129E LaunchPad     |        |
| STM32F407G-DISC1       |        |
| STM32L476RG Nucleo     |        |