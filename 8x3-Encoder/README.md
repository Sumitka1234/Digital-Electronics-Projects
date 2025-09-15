# 8x3 Encoder (Built Using Logic Gates)

## 📖 Overview
An **Encoder** is a combinational logic circuit that converts 8 input lines into 3 output lines.  
Instead of using a ready-made Encoder IC (like 74148), I implemented the circuit using **basic logic gates ICs** on a breadboard.

- Number of inputs: 8 (I0 – I7)  
- Number of outputs: 3 (Y2, Y1, Y0)  

## ⚡ Logic Expressions
For 8-to-3 Encoder, the outputs can be expressed as:  

- Y0 = I1 + I3 + I5 + I7  
- Y1 = I2 + I3 + I6 + I7  
- Y2 = I4 + I5 + I6 + I7  

(where `+` = OR operation)

## ⚡ Truth Table

| Active Input | Output (Y2 Y1 Y0) |
|--------------|-------------------|
| I0           | 000 |
| I1           | 001 |
| I2           | 010 |
| I3           | 011 |
| I4           | 100 |
| I5           | 101 |
| I6           | 110 |
| I7           | 111 |

## 🛠 Components Used
- IC 7404 (NOT gates, if required)  
- IC 7432 (OR gates)  
- Breadboard  
- LEDs for output visualization  
- Connecting wires  
- Power supply  

## 📷 Project Images
# 8x3 Encoder (Built Using Logic Gates)

## 📖 Overview
An **Encoder** is a combinational logic circuit that converts 8 input lines into 3 output lines.  
Instead of using a ready-made Encoder IC (like 74148), I implemented the circuit using **basic logic gates ICs** on a breadboard.

- Number of inputs: 8 (I0 – I7)  
- Number of outputs: 3 (Y2, Y1, Y0)  

## ⚡ Logic Expressions
For 8-to-3 Encoder, the outputs can be expressed as:  

- Y0 = I1 + I3 + I5 + I7  
- Y1 = I2 + I3 + I6 + I7  
- Y2 = I4 + I5 + I6 + I7  

(where `+` = OR operation)

## ⚡ Truth Table

| Active Input | Output (Y2 Y1 Y0) |
|--------------|-------------------|
| I0           | 000 |
| I1           | 001 |
| I2           | 010 |
| I3           | 011 |
| I4           | 100 |
| I5           | 101 |
| I6           | 110 |
| I7           | 111 |

## 🛠 Components Used
- IC 7404 (NOT gates, if required)  
- IC 7432 (OR gates)  
- Breadboard  
- LEDs for output visualization  
- Connecting wires  
- Power supply  

## 📷 Project Images
## 📷 Project I
![8x3 Encoder Setup](8x3 encoder.jpg.png)


## 🎯 Learnings
- Implemented Encoder logic **without using a dedicated IC**  
- Learned how to minimize boolean expressions for hardware design  
- Practiced breadboard wiring and debugging  
## 🎯 Learnings
- Implemented Encoder logic **without using a dedicated IC**  
- Learned how to minimize boolean expressions for hardware design  
- Practiced breadboard wiring and debugging  
