# Engs 21 Project
## Junfei Yu, Jack.M.Leonovicz Feb. 2017

### Introduction

This code is the software part for our final project of Engineering 21: Introduction to Engineering at Thayer Engineering School at Dartmouth College.

#### Current problem:

The Hanover Public Services, at Hanover, New Hampshire, has been using the next generation solution of cleaning the snow during the winter. They sprayed a mixed deicer, which has 24% salt diluted in H2O and CaCl2 before the snow coming to prevent the snow from building up and make the snow plowing process much easier. However, they have no mathematics models or computer knowledge to find out the most optimal density of the deicers. Sometimes the wrong density might result in economic lost and environment problems.

##### Solution: 

We built a system to help optimizing the deicers solution spraying for the Hanover Public Services at Hanover, New Hampshire. 

This code is for Arduino prototype usage of the software part of the sytem. We used three LED lights to indicate three different density combinations of the two chemical deicers. We used Pulse Width Modulation (PWM) code to control the spinning speeds of the two motors using a potentiomenter. 


### Usage

We mapped different ranges on a potentiomenter to the Arduino board. By connecting the power source, the potentiomenter, the LED lights, the transistors and motors which control the hardware(pipe) system, we could change the spinning speed of the two motors. Therefore, the system could give three different ranges of the combinations of the two deicers. The red, green and yellow LED lights each indicate a range during the real-time operation.
