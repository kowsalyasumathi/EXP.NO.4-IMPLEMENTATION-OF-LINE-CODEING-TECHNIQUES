# EXP.NO.4-IMPLEMENTATION-OF-LINE-CODEING-TECHNIQUES

3.Implementation of Line Codeing Techniques 
  
## AIM    
 The objective of this experiment is to study the Line coding techniques using the trainer kit. 
## APPARATUS REQUIRED
Trainer Kit, DSO(10MHz) , Patch Cords and Power Supply (0-30V)   
## PROCEDURE
```
1.Input the Digital Data
2.Accept the digital binary data stream (e.g., 10100111) as input.
3.The data can be either in NRZ (Non-Return-to-Zero), AMI (Alternate Mark Inversion), etc.
4.Select the Line Coding Scheme
5.Choose a line coding technique based on the application and channel requirements.
6.Map Bits to Signal Levels
7.Define how bits are represented using voltage levels:
         i)1 might be +V, 0 might be 0V in Unipolar NRZ.
8.In Biphase level, 1 is high-to-low, 0 is low-to-high transition.
9.For AMI, alternate 1s have alternating +V and -V, and 0s are 0V.
10.Apply the Encoding Logic
11.Iterate through the binary data.
12.For each bit, apply the logic based on the selected scheme to convert bits into signal levels or transitions.
13.Generate the Line Code Signal
14.Create a time-domain waveform representation.
15.Each signal element corresponds to a bit duration.
16.Store or transmit this encoded signal.
17.Transmit the Signal
18.Send the line-coded signal through the communication channel (e.g., coaxial cable, fiber optic, twisted pair).
```
## CIRCUIT DIAGRAM
![image](https://github.com/user-attachments/assets/eada3117-24f0-4b1b-af16-11f91bfc4208)

## MODEL GRAPH
![image](https://github.com/user-attachments/assets/7dbbb290-d5d5-41a3-bd97-4e9db1cb608d)

## TABLE


## OUTPUT GRAPHS
![output](https://github.com/user-attachments/assets/6adfd457-f427-438a-a38c-0c70c2045412)



## RESULT 
Thus the line coding techniques were successfully implemented for the given input data and verified experimentally.
