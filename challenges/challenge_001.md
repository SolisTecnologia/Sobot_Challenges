# Challenge 001 - SOBOT STARTER

## 🎯 Challenge Description
The goal of this challenge is to train the programmers to use all the concepts of movement with SoBot, along with activating the LED strip to signal each change of direction.

### Basic
Participants must program the SoBot to execute a sequence of movements using **fixed commands**, and during each change of direction, the LED strip must be activated to indicate the corresponding direction. For turns, use self-axis turns.

The movement sequence and LED colors are:
|N° | Direction| Led Color|
|--|--| -- |
|1|Forward | Green
|2|Left | Blue
|3|Forward | Green
|4|Right| Yellow
|5|Forward | Green
|6|Backward | Red
|7|Right| Yellow
|8|Forward | Green
|9|Right| Yellow
|10|Forward | Green
|11|Right| Yellow

![Path](./imgs/challenge_001_path.png)

### Intermediate
Perform the same path as the previous task, now with **continuous movement** and **differential turns**.


### Advanced
Execute the same path as the previous tasks using motor control in **pulses-per-second mode**, allowing **any type of turn**.


## 🥇 Completion Requirements
- **File Generation:** A different file must be generated for each difficulty level.
- **Complete Execution:** The SoBot must complete the entire sequence without errors.
- **Correct Use of Commands:** Commands must be applied correctly for each difficulty level.
- **Proper Signaling:** The LED strip must accurately indicate each direction change.


## 🌟 Tips
- Refer to the **Commands used for movement in fixed commands mode** section in the Command Guide.
- Refer to the **Set of commands used for movement in continuous mode** section in the Command Guide.
- Refer to the **Motor control commands in Pulses-per-Second mode** section in the Command Guide.
- Check out the example program on GitHub:[Simple Route](https://github.com/SolisTecnologia/SoBot-Simple-Route)