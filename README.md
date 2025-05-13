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
![image](https://github.com/user-attachments/assets/3a1da31c-a51b-4bbc-bbca-5fa214c71f65)

![image](https://github.com/user-attachments/assets/f4453e2d-a34b-4055-8226-b4efc5be86fa)

**Procedure**

1. Type the program in Quartus software.
2. Compile and run the program.
3. Generate the RTL schematic and save the logic diagram.
4. Create nodes for inputs and outputs to generate the timing diagram.
5. For different input combinations generate the timing diagram.

**Program:**

![image](https://github.com/user-attachments/assets/24cc44c3-a869-4130-b268-108702558ef8)


![image](https://github.com/user-attachments/assets/e67dc43a-a5f6-410e-a744-e79b9566e9c5)


Developed by: THARUN DANIEL Y

RegisterNumber: 212224050054



**RTL Schematic**

![image](https://github.com/user-attachments/assets/f63d60b0-5706-4545-9675-fe3556c5304e)

![image](https://github.com/user-attachments/assets/1b1a9e47-85d3-4722-8332-5771456bacc1)

**Output Timing Waveform**

![image](https://github.com/user-attachments/assets/6dbb4f1c-5b9b-4ef2-a2d4-e95b73abbd20)

![image](https://github.com/user-attachments/assets/41639724-ab98-469b-bba4-420bcb9f4a6b)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



