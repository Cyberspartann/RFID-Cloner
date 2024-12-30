# RFID Cloner with Arduino Nano

This project allows you to clone RFID tags using an **Arduino Nano** microcontroller and an RFID reader module (e.g., **MFRC522**). The system works by reading RFID tags and duplicating their data onto new tags, making it useful for applications like security systems, access control, and other environments that use RFID-based identification.

## Key Features:
- **Tag Cloning**: Read and duplicate RFID tags (e.g., 13.56 MHz or 125 kHz tags) using a simple interface.
- **Arduino Nano**: Compact and cost-effective microcontroller for a small-scale solution.
- **SPI Communication**: Utilizes the SPI interface to communicate with the RFID module, ensuring reliable and efficient data transfer.
- **User-Friendly**: The project is easy to set up and use, making it suitable for both beginners and experienced developers.

## Hardware Components:
- **Arduino Nano**: The central microcontroller for the system.
- **RFID Reader Module**: For reading and writing RFID tags (e.g., MFRC522).
- **RFID Tags**: Tags to read from and write to for cloning.
- **Jumper Wires**: To connect the RFID reader to the Arduino Nano.

## Pinout and Wiring:
The RFID reader module is connected to the Arduino Nano via the SPI interface. Here’s the pin mapping:


| **RFID Module Pin** | **Arduino Nano Pin** |
|---------------------|----------------------|
| RST/Reset           | D9                   |
| SPI SS              | D10                  |
| SPI MOSI            | D11                  |
| SPI MISO            | D12                  |
| SPI SCK             | D13                  |


# How It Works:
Read a Tag: Place an RFID tag near the reader to capture its data.
Clone the Tag: The captured data is written onto another RFID tag.
Test the Clone: Use the cloned RFID tag to ensure it works with the original system.
This RFID cloner is perfect for DIY projects or anyone looking to explore RFID technology with an easy-to-use setup. It works with the Arduino IDE and requires basic wiring to get started.



