# BALQUAD - STM32F767ZI Quadcopter Flight Controller



BALQUAD is a quadcopter flight controller project developed step-by-step using the **NUCLEO-F767ZI** development board and **STM32 HAL drivers**.



The project follows the development stages of the M-HIVE STM32 Drone Programming Course firmware while adapting the implementation from **STM32F405 + LL drivers** to **STM32F767ZI + HAL drivers**.



## Hardware



* MCU: STM32F767ZI

* Development Board: NUCLEO-F767ZI

* IDE: STM32CubeIDE

* Driver Library: STM32 HAL



## Development Progress



* [x] V1.1 - Debug LED

* [ ] V1.2 - Debug Buzzer

* [ ] V1.3 - Debug UART

* [ ] V2.1 - BNO080

* [ ] V2.2 - ICM20602

* [ ] V2.3 - LPS22HH

* [ ] GPS

* [ ] RC Receiver

* [ ] ESC / Motor PWM

* [ ] EEPROM

* [ ] Battery Monitoring

* [ ] Telemetry

* [ ] Safety / Failsafe

* [ ] PID Control

* [ ] Roll \& Pitch Control

* [ ] Yaw Rate Control

* [ ] Yaw Heading Control







The first stage verifies the basic GPIO functionality of the NUCLEO-F767ZI board.



The three onboard LEDs are controlled using STM32 HAL GPIO functions.



### Used Pins


* LD1: PB0

* LD2: PB7

* LD3: PB14






## Reference



This project is based on the development path of:



**M-HIVE STM32 Drone Programming Course - MH-FC-FW1.0**



Original repository:



`ChrisWonyeobPark/M-HIVE-STM32\_drone\_programming\_course-MH-FC-FW1.0`



The original firmware targets STM32F405 and uses STM32 LL/HAL drivers. BALQUAD is being reimplemented and adapted for the STM32F767ZI platform with STM32 HAL.



## License



The reference project is distributed under the GNU General Public License v3.0. Any reused or modified source code from the original project should remain compliant with the applicable GPLv3 terms.



