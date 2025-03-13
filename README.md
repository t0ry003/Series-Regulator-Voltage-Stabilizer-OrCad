# Series Regulator Voltage Stabilizer (ERS)

## Overview
This project is a **Series Regulator Voltage Stabilizer (ERS)** designed to maintain a stable output voltage despite variations in input voltage and load conditions. The system leverages **error amplifiers, negative feedback loops, and protective circuits** to ensure high precision, efficiency, and reliability.

Developed as part of an academic project at the **Polytechnic University of Bucharest - Faculty of Electronics, Telecommunications, and Information Technology**, this stabilizer serves as a practical implementation of **linear voltage regulation**.

## Features
- **Precise Voltage Regulation**: Maintains a stable output voltage using an operational amplifier-based error correction system.
- **Negative Feedback Control**: Ensures accuracy by continuously comparing output voltage with a reference voltage.
- **Thermal Protection**: Automatic shutdown in case of overheating to prevent component damage.
- **Current Limiting**: Prevents excessive current draw, protecting the circuit and connected devices.
- **High Efficiency**: Optimized component selection to minimize power dissipation and improve thermal performance.

## System Design
The stabilizer consists of the following key elements:
1. **Error Amplifier**: Uses an operational amplifier in a non-inverting configuration to compare the output voltage with a reference.
2. **Voltage Reference Generator**: A Zener diode-based system provides a stable reference voltage.
3. **Series Regulating Element (ERS)**: Implements a **Darlington transistor configuration** to control the output voltage.
4. **Protection Mechanisms**:
   - **Overcurrent Protection**: Detects excessive load currents and limits output.
   - **Overtemperature Protection**: Monitors and prevents overheating of key components.

## Schematic Diagram
poza

## PCB Design
This project includes a **fully designed PCB layout**, which can be fabricated for practical testing and implementation.
poza
poza 3d

## Simulations & Testing
Multiple simulations have been conducted to verify:
- **Output voltage stability across different input voltages (36V-40V)**
- **Response to load variations**
- **Thermal response and efficiency**
- **Gain characteristics of the error amplifier**

## How to Use
1. **Power Input**: Connect a **36V-40V DC** power source to the input terminals.
2. **Adjust Output Voltage**: Fine-tune using the onboard potentiometer (adjustable from **10V to 20V**).
3. **Monitor Performance**: Use an oscilloscope or multimeter to verify the output voltage and ensure stable operation.
4. **Safety Measures**: Ensure adequate heat dissipation and do not exceed the rated current limits.

## Bill of Materials (BOM)
| Qty | Ref | Part Number |
|-----|-----|------------|
| 1   | D1  | BZX84-C6V2 |
| 1   | D2  | BZX84-C2V7 |
| 2   | J1, J2 | CON2 |
| 2   | LED1, LED2 | MLED81 |
| 2   | P1, P2 | 5k |
| 4   | Q1, Q2, Q3, Q4 | QBC856B |
| 4   | Q5, Q6, Q7, Q9 | QBC846B |
| 1   | Q8  | QMJD31C |
| 7   | R1, R2, R3, R7, R8, R9, R15 | 1k |
| 1   | R4  | 510 |
| 1   | R5  | 330 |
| 1   | R6  | 470 |
| 2   | R10, R12 | 1.5k |
| 1   | R11 | 2.7K |
| 1   | R13 | 4.7k |
| 1   | R14 | 220 |
| 2   | R16, R17 | 10K |
| 3   | R18, R20, R25 | 0.47 |
| 1   | R19 | 680 |
| 1   | R21 | 5.6k |
| 5   | R22, R23, R24, R26, R27 | 3.9k |
| 2   | R28, R29 | 820 |


## Applications
- **Power supply modules** requiring stable voltage regulation;
- **Embedded systems** where voltage precision is crucial;

## License
This project is open-source and can be used or modified under the **MIT License**.

## Contact & Credits
Developed by: **Olteanu Rareș Cristian**  
Institution: **Polytechnic University of Bucharest**  
Supervisor: **Drăghici Florin**  
