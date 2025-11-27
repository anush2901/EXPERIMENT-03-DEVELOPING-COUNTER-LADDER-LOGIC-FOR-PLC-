# EXPERIMENT-03-DEVELOPING-COUNTER-LADDER-LOGIC-FOR-PLC-
## NAME : ANUSHMALIKA R
## REGISTER NUMBER : 212224230020
## DEPARTMENT : AIDS
## YEAR : II

### Aim:
To understand and implement various counter operations in Programmable Logic Controller (PLC) ladder logic.

### Apparatus Required:
Programmable Logic Controller (PLC): A PLC that supports counter functions.
PLC Programming Software: Software such as RSLogix, TIA Portal, or CX-Programmer.
Computer System: For programming and simulating the PLC ladder logic.
Input Devices: Push buttons or switches to trigger the counter operations.
Output Devices: LEDs or other indicators to visualize the counter outputs.
Wires and Connectors: For interfacing input/output devices with the PLC.
Power Supply: Appropriate power supply for the PLC and peripherals.

### Theory:
Counters in PLCs are used to count events or occurrences, such as the number of items passing on a conveyor belt, the number of cycles a machine runs, or how many times a process has started or stopped. Counters are commonly used in automation to perform tasks like stopping a machine after a set number of products or signaling a notification when a count reaches a specific value.

### Types of Counters:
Up Counter (CTU) Functionality:

The up counter counts every time the input condition becomes TRUE (ON). When the accumulated value reaches the preset value, the counter output becomes TRUE. If the reset input is triggered, the counter resets to zero.
Down Counter (CTD) Functionality:

The down counter decreases the count every time the input condition becomes TRUE (ON). When the count reaches zero, the counter output becomes TRUE. The counter can be reset by a reset input to the preset value.
Up/Down Counter (CTUD) Functionality:

The up/down counter can increment or decrement the count based on two different inputs. One input increments the count, while the other decrements it. When the count reaches the preset value or zero, the respective outputs become TRUE. The counter can be reset as required.


### Procedure:
Setup the PLC Programming Environment:
Connect the PLC to the computer and launch the PLC programming software.
Ensure all input and output devices are connected to the PLC’s I/O modules.
Create Ladder Logic for Counters:
Up Counter (CTU):

Create a rung with an input (e.g., a push button) linked to a CTU instruction.
Set the preset value (e.g., 10 counts). Assign an output to indicate when the preset value is reached.
Down Counter (CTD):

Create a rung with an input linked to a CTD instruction.
Set the preset value (e.g., 5 counts). Assign an output to indicate when the counter reaches zero.
Up/Down Counter (CTUD):

Create a rung with separate inputs for counting up and counting down.
Set the preset value (e.g., 8 counts). Assign outputs for when the count reaches the preset value or zero.
Simulate the Ladder Logic:
Up Counter (CTU):

Run the simulation in the PLC software. Press the input button repeatedly and observe the counter increment until the preset value is reached, at which point the output activates.
Down Counter (CTD):

Run the simulation, press the input button repeatedly, and observe the counter decrement. When the counter reaches zero, the output activates.
Up/Down Counter (CTUD):

Simulate both the up and down counting inputs. Observe how the counter increments or decrements and how the output is activated when the count reaches the preset value or zero.
Download and Execute:
Download the ladder logic program to the PLC if available and run it.
Test the counters with the physical push buttons and observe the LEDs or other output devices.
### Outputs:
Up Counter (CTU): The output LED or indicator should activate when the preset count (e.g., 10) is reached.
Down Counter (CTD): The output should activate when the count reaches zero.
Up/Down Counter (CTUD): The output should activate when the count reaches the preset value or zero, depending on the inputs.

### Simulation Screenshots:
## counter

<img width="1919" height="1014" alt="image" src="https://github.com/user-attachments/assets/19ae131a-7984-4452-92a2-ec56b7bdc6b6" />
<img width="1919" height="1023" alt="image" src="https://github.com/user-attachments/assets/139e5e2e-f1fe-42a6-86b7-c8c89623110a" />
<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/5a03dc73-4d67-4192-8490-1ebcb083aead" />
<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/c37393de-2f66-4cd1-9a88-4552e80aeb4d" />
<img width="1907" height="1018" alt="image" src="https://github.com/user-attachments/assets/ef409f1a-ac24-4f92-8aca-4c2e9d6b4f80" />
<img width="1919" height="1017" alt="image" src="https://github.com/user-attachments/assets/56e7ff94-6429-4c50-9082-d4808428aa42" />

## up counter

<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/f6dd6e0b-767a-4509-ae66-eab09ce17d37" />
<img width="1501" height="200" alt="image" src="https://github.com/user-attachments/assets/059fa222-2b00-4935-ae38-d88c15299a2f" />

## down counter

<img width="1463" height="647" alt="image" src="https://github.com/user-attachments/assets/f23fd7e2-6b27-42bf-ba9d-583410d4b6f7" />
<img width="1351" height="375" alt="image" src="https://github.com/user-attachments/assets/28497cbe-10c4-4c2a-9a80-f6b2c5049477" />
<img width="1502" height="229" alt="image" src="https://github.com/user-attachments/assets/99bde22e-794d-40d3-a682-269a4a201bb4" />
<img width="1504" height="339" alt="image" src="https://github.com/user-attachments/assets/293d4b98-6bf7-4987-8544-1cffd01764b6" />
<img width="1509" height="312" alt="image" src="https://github.com/user-attachments/assets/9470a0b7-5a15-410f-83a9-d34c683c447f" />

## up/down counter-1

<img width="1606" height="651" alt="image" src="https://github.com/user-attachments/assets/85ab70ee-e2a1-4606-b2e0-b35ae4b6a657" />
<img width="1406" height="548" alt="image" src="https://github.com/user-attachments/assets/a4500084-431e-4f4b-afd7-25c89e73e401" />
<img width="1505" height="220" alt="image" src="https://github.com/user-attachments/assets/f50f5fca-84d6-465d-bd75-bef2341b1487" />
<img width="1503" height="193" alt="image" src="https://github.com/user-attachments/assets/486a57b8-df23-4397-b050-f207c03057ac" />
<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/d57c0d95-4bf1-41e4-a569-8fb9baa0a2ef" />
<img width="1919" height="1025" alt="image" src="https://github.com/user-attachments/assets/921a1a69-46f8-4c8e-92d6-2092f181a49e" />

## up/down counter-2

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/9506580e-d691-4097-b817-32e19c570388" />
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/a919e690-af3e-4f70-a4c6-272421d59723" />
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/babba536-59bc-44fe-aa48-56afea68ac9b" />

### Results:
The ladder logic programs for Up Counter (CTU), Down Counter (CTD), and Up/Down Counter (CTUD) were successfully implemented and tested. The outputs behaved as expected, indicating correct counting operations. The experiment demonstrated how counters are essential in automation for counting events and managing process sequences.
