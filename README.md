# CH32V003-DevBoard
CH32V003 Microcontroller Development Board
Overview
This is an open-source development board based on the CH32V003 microcontroller. The board includes USB Type-C connectivity, voltage regulation, SWD programming header, USB-to-UART interface, and accessible GPIO headers—designed for rapid prototyping and embedded development.

Features
MCU: CH32V003F4U6 (RISC-V microcontroller)

USB Type-C for power and programming

3.3V LDO Regulator (LPS0707)

CH340N USB-to-UART converter

SWD header for debugging/programming

On-board reset button and LED indicator

Pin headers for all GPIOs

Small breadboard-friendly form factor
Folders
/hardware — KiCad schematics, PCB layout, and 3D models

/ibom — Interactive HTML Bill of Materials (ibom.html)

/images — Rendered images, assembly photos

Getting Started
Build the hardware: Use the KiCad files to fabricate the board and source components as per the BOM.

Programming: Use an SWD programmer/debugger for flashing code, or USB-UART for serial communication.

Power Up: Connect to USB Type-C for power and data.

File List
ibom.html: Interactive BOM for component placement and assembly

3d_1.jpg, 3d_2.jpg: 3D renders

PCB.jpg: PCB top layout image

Schmeatic.jpg: Full circuit schematic

Acknowledgements
Hardware design created with KiCad EDA

