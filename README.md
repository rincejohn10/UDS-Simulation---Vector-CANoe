🛠️ DIAGNOSTICS - UDS SIMULATION (VECTOR CANOE)

This project demonstrates the simulation and testing of UDS (Unified Diagnostic Services) using Vector CANoe and CAPL. It emulates various diagnostic request/response cycles over CAN, useful for testing ECUs, diagnostic tools, or learning UDS protocols.

📁 Files
`Configuration1.cfg´: Vector CANoe configuration file

´Diag_req.can´: CAPL script that handles request from Diagnostic ECU
´Diag_res.can´: CAPL script that handles response Diagnostic ECU


▶️ How to Use
1. Open Vector CANoe.
2. Load the project using the Configuration1.cfg file.
3. Make sure the capl file is attached to the diagnostic simulation node.
4. Start measurement. Use the Diagnostic Console or manually trigger UDS services.
5. Watch request/response patterns in the Trace Window.

🌟 Highlights
🔍 Simulated essential UDS services such as:

0x10: Diagnostic Session Control
0x11: ECU Reset
0x3E: Tester Present

📜 Implemented CAPL logic to decode UDS requests and respond accordingly.

🧪 Useful for testing OBD tools, validating ECU diagnostics, or learning UDS protocols.

🔌 Emulates UDS over standard CAN protocol (UDS on CAN).

👤 Author
Rince John
