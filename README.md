# Poker-Table-Master-Controller
Developed on MacOS with CCS Theia on MSP430.

This repo used to run a custom hardware RFID tracking poker table. The master sytem receives information from player boxs and sends it to a computer. The code is written using 
the Energia IDE and utilizes a premade MFRC522 library in C++. The master system that communicates with the player boxes is written in C and i used the CSS IDE from TI to develop. 
All firmware is uploaded onto x8 MSP430FR2355. They are using SPI to talk with MFRC522 and I2C to share card information.

6/25/2024 - The master system is ready for furthur dev. The UART Connection needs to be implamented.
            The cards need Serial values
