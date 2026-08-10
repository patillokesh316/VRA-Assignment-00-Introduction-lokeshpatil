# Assignment 00 — Student Answer Sheet

## Student Information

| Field | Student Response |
|---|---|
| Full name | `[Lokesh Ravindra Patil]` |
| GitHub username | `[patillokesh316]` |
| Class/college | `[shankarlal khandelwal college akola]` |
| Submission date | `[10-08-2026]` |

---

## Section A — Industrial Automation Fundamentals (15 marks)

### Q1. What is industrial automation? Explain it in 3–5 sentences. (5 marks)

`Industrial automation means using machines and technology to do industrial work automatically with less human effort. It helps factories produce products faster, more accurately, and with fewer mistakes. Devices like PLCs, sensors, robots, and control systems are commonly used in automation. It is mainly used to make industrial work easier, safer, faster, and more efficient.`

### Q2. State any four reasons industries use automation. (4 marks)

1. `To increase production speed and efficiency.`
2. `To reduce human errors and improve product quality.`
3. `To reduce production costs and save time.`
4. `To improve worker safety in dangerous environments.`

### Q3. Give three examples of processes that can be automated using PLC and SCADA. (3 marks)

1. `Water level and pump control system. `
2. `Conveyor belt control in manufacturing industries.`
3. `Temperature and pressure control in industrial plants.`

### Q4. Complete the automation sequence. (3 marks)

```text
Input → PLC → Output → SCADA Monitoring
```

Explain the meaning of each stage:

`1.	Input – Sensors collect information from the machine or process, such as temperature, level, or pressure.
2.	PLC – The PLC receives the information and makes decisions based on the programmed instructions. 
3.	Output – The PLC sends commands to devices like motors, pumps, valves, or alarms to perform the required action. 
4.	SCADA Monitoring – SCADA shows the process information on a computer screen so the operator can monitor and control the system.`

---

## Section B — PLC Fundamentals and Working (25 marks)

### Q5. Expand PLC and explain why it is called an industrial computer. (5 marks)

`PLC stands for Programmable Logic Controller. It is called an industrial computer because it can receive input signals, process them according to a program, and control output devices. PLCs are specially designed to work in industrial environments and can handle heat, dust, vibration, and electrical noise. They are commonly used to control machines and automatic processes in factories.`

### Q6. Classify each device as a PLC input or PLC output. (5 marks)

| Device | Input or Output? |
|---|---|
| Push button | `Input` |
| Proximity sensor | `Input` |
| Motor contactor | `Output` |
| Indicator lamp | `Output` |
| Temperature sensor | `Input` |

### Q7. Write the three main PLC working steps in the correct order. (6 marks)

1. `Input Scan – The PLC reads signals from input devices such as sensors and push buttons.`
2. `Program Execution – The PLC processes the inputs according to the programmed logic.`
3. `Output Scan – The PLC sends signals to output devices such as motors, lamps, and valves.`

### Q8. What is a PLC scan cycle? Why must it repeat continuously? (5 marks)

`A PLC scan cycle is the process in which the PLC reads inputs, executes the program, and updates the outputs. This process happens very quickly and then starts again. It must repeat continuously so the PLC can monitor changes in the machine and respond to them immediately. This helps the machine work safely and automatically.`

### Q9. Identify the PLC section responsible for each function. (4 marks)

| Function | PLC Section |
|---|---|
| Executes the user program | `CPU` |
| Stores the program and data | `Memory` |
| Reads field-device signals | `Input Module` |
| Controls external devices | `Output Module` |

---

## Section C — SCADA Fundamentals (20 marks)

### Q10. Expand SCADA and explain its purpose. (5 marks)

`SCADA stands for Supervisory Control and Data Acquisition. It is a system used to monitor and control industrial processes from a computer. SCADA collects information from machines, sensors, and PLCs and displays it on a screen for the operator. Its main purpose is to help operators monitor the process, detect problems, and control equipment easily.`

### Q11. State five important functions of a SCADA system. (5 marks)

1. `Monitoring the industrial process in real time. `
2. `Collecting data from sensors and PLCs. `
3. `Controlling machines and equipment remotely. `
4. `Giving alarms when a problem or abnormal condition occurs. `
5. `Storing and displaying process data for analysis and reporting. `

### Q12. Why is SCADA described as the “eyes” of an automation system? (4 marks)

`SCADA is called the “eyes” of an automation system because it allows operators to see what is happening in the industrial process. It displays information such as temperature, pressure, speed, and machine status on a computer screen. It also shows alarms when something goes wrong, helping operators monitor and control the system easily.`

### Q13. Name four industries or services where SCADA can be used. (4 marks)

1. `Power and electricity industry`
2. `Water treatment and supply`
3. `Oil and gas industry `
4. `Manufacturing industry`

### Q14. What is the difference between monitoring and controlling? (2 marks)

`Monitoring means observing and checking the status of a machine or process without directly changing it. For example, SCADA can show the temperature of a machine on a screen.
Controlling means giving commands to a machine or process to change its operation. For example, an operator can start or stop a motor using SCADA.
In short: Monitoring = watching the process, while Controlling = changing or operating the process.`

---

## Section D — PLC, HMI and SCADA Relationship (15 marks)

### Q15. Complete the comparison table. (9 marks)

| System | Main purpose | Typical user/location | Example task |
|---|---|---|---|
| PLC | `Controls machines and processes` | `Factory floor / control panel` | `Starting and stopping a motor` |
| HMI | `Allows the operator to monitor and control a machine` | `Operator station / machine panel` | `Changing motor speed or setting temperature` |
| SCADA | `Monitors and controls large industrial processes` | `Control room / central computer` | `Monitoring multiple machines and showing alarms` |

### Q16. Explain how information travels from a field sensor to a SCADA screen. (6 marks)

`A field sensor first detects a physical condition such as temperature, pressure, level, or speed and sends the signal to the PLC. The PLC receives and processes this signal according to its programmed instructions. The processed information is then sent through a communication network to the SCADA system. SCADA receives the information and displays it on the computer screen using values, graphs, indicators, or alarms. This allows the operator to easily monitor what is happening in the industrial process.`

---

## Section E — Industrial Application Challenge (15 marks)

### Scenario: Automatic Water Tank

A tank must fill automatically. A low-level sensor detects when water is low, and a high-level sensor detects when the tank is full. A pump supplies water. The operator should see the tank and pump status on a monitoring screen.

### Q17. Identify the PLC inputs and output. (3 marks)

- Inputs: `Push button, proximity sensor, temperature sensor `
- Output: `Motor contactor, indicator lamp, control valve`

### Q18. Write the required control behaviour in plain language. (4 marks)

`The control system should continuously check the input signals from sensors and push buttons. When the required condition is detected, the PLC should turn ON the appropriate output device, such as a motor, lamp, or valve. When the condition is no longer present, the PLC should turn the output OFF. This process should repeat continuously to keep the machine operating safely and correctly.`

### Q19. State four items that should be visible on the SCADA/HMI screen. (4 marks)

1. `Machine status (ON/OFF)`
2. `Sensor values such as temperature, pressure, or level `
3. `Alarms and warning messages `
4. `Start/Stop control buttons`

### Q20. Suggest one alarm and one value/event that should be recorded. (4 marks)

- Alarm: `High temperature alarm when the temperature exceeds the safe limit.`
- Recorded value/event: `Temperature value and the time when the alarm occurred.`

---

## Submission Checklist

- [x] I entered my student information.
- [x] I answered Questions 1–20.
- [x] I used my own words.
- [x] I checked spellings and technical terms.
- [x] I completed `student-work/reflection.md`.
- [x] I made at least three meaningful commits.
- [x] I checked the Actions result.
- [x] I submitted my repository link to Prof. Dattaraj Vidyasagar.
