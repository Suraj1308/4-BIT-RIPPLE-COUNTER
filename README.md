# 4-BIT-RIPPLE-COUNTER

**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 Bit Ripple Counter**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

**Procedure**

/* write all the steps invloved */
```
1.Open quartus II and create New project wizard.
 2. Write the program in Verilog HDL file and run the program.
 3. Download the RTL viewer
 4. Now open university program VWF and download waveform after the execution.
```

**PROGRAM**

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

 Developed by:ARSHATH HUSSAIN.I RegisterNumber:21224230022
*/
![435462968-a2960aee-c520-4add-b4ee-1755f0030a54](https://github.com/user-attachments/assets/c9dfcdbb-7eaf-414f-ad55-d8285fa3eafa)

endmodule // Full Adder Module module full_adder ( input A, B, Cin, // Inputs: A, B, and Carry-in output Sum, Cout // Outputs: Sum and Carry-out );

![435462987-563a8ca9-6c57-49c9-a4e7-d568a379cb53](https://github.com/user-attachments/assets/c2872474-0115-4f04-b60d-561363e50b64)

end module


**RTL LOGIC FOR 4 Bit Ripple Counter**

![435463056-67b5c71b-2efc-4c1c-8a2e-8866bef2a283](https://github.com/user-attachments/assets/efe5e77b-c18a-465d-8e57-fbb19ea6d3ac)

**TIMING DIGRAMS FOR 4 Bit Ripple Counter**

![435463065-ad5f42e7-8ebb-4579-800c-d3c35725303f](https://github.com/user-attachments/assets/8b50b669-8d93-4eba-aaec-d48185001443)


**RESULTS**

Thus the 4 Bit Ripple Counter is executed using verilog and verified with its Truth table.
