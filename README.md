# FULL_ADDER_SUBTRACTOR
Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**
To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.
**Equipments Required:**
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
**Full Adder and Full Subtractor**
**Full Adder**
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.
Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 
Carry = AB + ACin + BCin
![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)
**Figure -1 FULL ADDER**
**Full Subtractor**
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.
![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)
Diff = A ⊕ B ⊕ Bin 
Borrow out = A'Bin + A'B + BBin
**Truthtable**
**Procedure**
Write the detailed procedure here

**Program:**
/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
<img width="899" height="320" alt="Screenshot 2025-11-21 180341" src="https://github.com/user-attachments/assets/0e2db8c5-ad7c-40bf-a157-fd8f518431ea" />
<img width="773" height="315" alt="Screenshot 2025-11-21 180842" src="https://github.com/user-attachments/assets/7fc4df6b-650a-49cd-a60f-21855e5fcfda" />
Developed by:Swetha.S Register Number:25017890
*/
**RTL Schematic**
<img width="1418" height="837" alt="Screenshot 2025-11-21 180153" src="https://github.com/user-attachments/assets/b1fe3750-c480-46cd-b5d2-d4cb0ae56adc" />
<img width="1687" height="730" alt="Screenshot 2025-11-21 180706" src="https://github.com/user-attachments/assets/b95ed428-1f13-4de2-a864-aad606b5e991" />
**Output Timing Waveform**
<img width="1697" height="395" alt="Screenshot 2025-11-21 180317" src="https://github.com/user-attachments/assets/d20fdf35-211f-46b8-b1d5-d72eb945cfd4" />
<img width="1709" height="351" alt="Screenshot 2025-11-21 180824" src="https://github.com/user-attachments/assets/50703eaf-6107-42ae-aef8-bf955f8b52eb" />
**Result:**
Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



