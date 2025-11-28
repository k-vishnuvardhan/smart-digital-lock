# Smart Digital Lock System (FPGA-Based)

A simulation-based Smart Digital Lock implemented on FPGA using Verilog.  
The system uses a 4x4 keypad as the input interface and a 7-segment display & LEDs for output indication.  
This project demonstrates secure password verification, lock/unlock logic, and digital system design principles.

---

##  Technologies & Tools
- **FPGA** (Simulation-based development)
- **Verilog HDL**
- **Xilinx ISE / Vivado (any simulation tool)**
- **4x4 Keypad Interface**
- **Seven-Segment Display**
- **LED Indicators**

---

##  Features
- Password-based authentication  
- Keypad input scanning  
- Real-time display of entered digits on 7-segment  
- LED indication:
  - **Green LED → Access Granted**
  - **Red LED → Access Denied**
- Reset and retry mechanism  
- Fully simulated on FPGA design tools

---

##  System Architecture
The system consists of the following blocks:

1. **Keypad Scanner Module**  
   - Detects keypress  
   - Converts keypad matrix to digital code

2. **Password Verification Module**  
   - Compares entered code with a predefined password  
   - Outputs match/mismatch signals

3. **7-Segment Display Driver**  
   - Displays digits during input  
   - Can show success/failure codes (optional)

4. **Control Unit (FSM)**  
   - Handles input state  
   - Implements lock/unlock logic  
   - Controls LEDs

---

##  Files in This Repository

src/ # Verilog source files
docs/ # Project documentation (optional)
sim/ # Testbench & simulation outputs
images/ # Waveforms / diagrams (optional)
README.md # Project overview
---

## How to Run (Simulation)
1. Open Xilinx ISE / Vivado / ModelSim  
2. Import all Verilog files from the **src/** folder  
3. Load the testbench file  
4. Run behavioral simulation  
5. Observe:
   - Keypad inputs  
   - 7-segment outputs  
   - LED states  
   - Password comparison results  

---

## Simulation Output (Optional)
Add your simulation screenshots here:
<img width="1536" height="1024" alt="Nov 28, 2025, 12_48_30 PM" src="https://github.com/user-attachments/assets/8943348a-1b65-4754-8ee3-467e13ba857d" />
---

## 📚 Learning Outcomes
- Digital system design using Verilog  
- Keypad matrix scanning technique  
- FSM design and control logic  
- Seven-segment interfacing  
- FPGA simulation workflow  

---





