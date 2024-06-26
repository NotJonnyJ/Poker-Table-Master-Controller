# Poker-Table-Master-Controller
Developed on MacOS with CCS Theia on MSP430.

These files are used to run a custom hardware RFID tracking poker table. The sytem reading information from a player is written using the Energia IDE and utilizes a premade MFRC522 library in C++. The master system that communicates with the player boxes is written in C and i used the CSS IDE from TI to develop. All firmware is uploaded onto x8 MSP430FR2355. They are using SPI to talk with MFRC522 and I2C to share card information.

As of 6/22/2024 I have modeled the basic electronics and firmware needed to read and collect inforamtion from players. Soon to be added will be, hardware specifications and 3D print files for electronic enclosures and custom PCBs.
