# The Time Manipulator

This repository contains schematic, design files and firmware for digital delay guitar effect pedal based on PT2399.
Effect pedal was inspired by [_The Time Manipulator_](https://www.electrosmash.com/time-manipulator) effect pedal.

Electro Smash's pedal is build using popular Arduino ATMEGA328P-PU chip. 
Solution found in this repositroy doesn't use the same microcontroller. It uses PIC16F72. Reason for that is I had those readily available.

Board is designed using surface mounted components (SMD).

## Block diagram
Effect pedal signal flow diagram is shown below. 
![image](https://github.com/user-attachments/assets/1e218f75-acb6-49e7-8b9a-b7f13842bf8a)

## Render images

![image](https://github.com/user-attachments/assets/d36be784-8824-447e-932b-f6c6a2ffa0aa)

![image](https://github.com/user-attachments/assets/34eba947-9bc3-40aa-a790-ae2d59ff9661)

![image](https://github.com/user-attachments/assets/2036f512-581d-4ff5-b6ee-b78cd99036fd)


## Schematics

## Layout

Board dimensions are 75 mm by 78 mm.
Board layout is done as 4 layer board.

![image](https://github.com/user-attachments/assets/fa902e97-4ac8-418b-9804-6f09f6c035a6)


### Front Cu layer:
![image](https://github.com/user-attachments/assets/1a1077c3-f0df-44ad-b8e0-bd0df1380432)

### In1. Cu layer:
![image](https://github.com/user-attachments/assets/7c73d51a-4de3-4ad0-8846-cb290e22a9bc)

### In2. Cu layer:
This layer has two power planes. Bigger one is for 5V supply, and the smaller one is for 9V supply.
![image](https://github.com/user-attachments/assets/fa978970-3983-405f-acd4-c4947d36de32)

### Back Cu layer:
![image](https://github.com/user-attachments/assets/00bdfabb-23f3-4e0c-8bc3-faa2a2a31881)


## Firmawrae
Firmware and PCB design of PT2399 IC based digital delay  effect guitar pedal
