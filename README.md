# 🔋 Battery Charge Display System for Bako Car

This project replaces the analog State of Charge (SoC) indicator on Bako vehicles with a real-time digital display using CAN bus data from the BMS.

📄 **Full Documentation**: [Battery Charge Display System for Bako Car.pdf](Battery%20Charge%20Display%20System%20for%20Bako%20Car.pdf)

## 🎯 Summary

- Reads SoC from the CAN bus (MCP2515 + Arduino Uno)
- Displays charge as a percentage using MAX7219 7-segment LED
- Powered safely using a DC-DC step-down converter (12V → 5V)

## 🧰 Technologies Used

- Arduino Uno  
- MCP2515 CAN interface  
- MAX7219 display driver  
- 7-segment LED display  
- DC-DC power module (6R1ML)

---

## 👨‍💻 Developed by

**Achref Abdellaoui** – Embedded Systems Engineer  
[GitHub Profile](https://github.com/achrefabdellaoui)
