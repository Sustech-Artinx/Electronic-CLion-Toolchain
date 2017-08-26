# RM2018 CLion Toolchain 
This project is built for cross-platform built on Mac and Windows on STM32. Target board is chosen for RM2017 dev board. 

## Hardware
1. RM2017 dev board
![image of RM2017 board](http://product1.djicdn.com/uploads/photos/760/medium_2c39c864-899e-42da-a75c-38668c16b793.jpg)
http://store.dji.com/cn/product/rm-main-controller-development-board

2. JLink SWD / JLink v8

## Windows
Using Keil uVision 5, open MDK-ARM/RMv3testDemo.uvprojx

## Mac
You need to set up the toolchain yourself.
* CLion
* gcc-arm-embedded
* JLink Debugger

Follow the steps on https://blog.jetbrains.com/clion/2016/06/clion-for-embedded-development/
The CMake.txt and cross-compile cmake file are inside the folder.
