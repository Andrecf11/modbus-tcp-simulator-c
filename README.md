# Modbus TCP/IP Simulator (C)

## 📌 About the Project
Developed during my curricular internship at Pragmasoft (ISEP), this project consists of a custom Modbus TCP/IP simulator written from scratch in C. 

While functional simulators exist on the market, I opted to build a custom tool to make the project more robust, ensuring total flexibility and adaptation to the specific testing requirements of the eHub platform (a smart microgrid management system).

## ⚙️ Features
- Implements the `Read Holding Registers (0x03)` function.
- Custom VBScript execution engine to automate test scenarios (e.g., battery charge/discharge, communication alarms).
- Non-blocking socket communication (select, accept, recv).
- Integrated console for manual register manipulation (GET/SET).
- Logging system for register changes.

## 🛠️ Technologies Used
- **Language:** C
- **Protocols:** Modbus TCP/IP, TCP/IP Sockets
- **Environment:** Linux (Ubuntu), VirtualBox
- **Database (for testing):** MySQL, DBeaver
- **Other:** VBScript (test scripts)
