# The Time Manipulator

<p align="center">
  <img src="https://github.com/user-attachments/assets/add52ed0-eb6d-45c2-a73b-62471b15cc37" alt="3D render" width="300"/>
  <img src="https://github.com/user-attachments/assets/1e218f75-acb6-49e7-8b9a-b7f13842bf8a" alt="Block diagram" width="600"/>
</p>

This repository contains schematic, design files and firmware for digital delay guitar effect pedal based on PT2399.
Effect pedal was inspired by [_The Time Manipulator_](https://www.electrosmash.com/time-manipulator) effect pedal.

Electro Smash's pedal is built using popular Arduino ATMEGA328P-PU chip. 
Solution found in this repositroy doesn't use the same microcontroller. It uses PIC16F72.

Board is designed using surface mounted components (SMD).

Aditionaly, I have written on effect pedal design, it can be found in the repository [Analogna Efekt Pedala](./Analogna%20Efekt%20Pedala.pdf) (it's in Serbian)

## First version of the board

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/f98e938d-9887-4372-864f-4a4a66107280" alt="Image 1" width="200"/></td>
    <td><img src="https://github.com/user-attachments/assets/72c27344-82cb-4cb2-9c92-6979e74377d1" alt="Image 2" width="200"/></td>
    <td><img src="https://github.com/user-attachments/assets/bb3fa088-5605-4743-977b-243b9401c95e" alt="Image 2" width="200"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/1e18355e-8ebe-4095-9a8f-a258416abe1a" alt="Image 3" width="200"/></td>
    <td><img src="https://github.com/user-attachments/assets/9d15bed4-8fb9-43c8-ad42-c9276e6c5d72" alt="Image 4" width="200"/></td>
    <td><img src="https://github.com/user-attachments/assets/fce24942-f342-4900-bc35-3f32ebbe8c5d" alt="Image 2" width="200"/></td>
  </tr>
</table>

Firmware and PCB design of PT2399 IC based digital delay  effect guitar pedal

## Render images

![image](https://github.com/user-attachments/assets/d36be784-8824-447e-932b-f6c6a2ffa0aa)

![image](https://github.com/user-attachments/assets/34eba947-9bc3-40aa-a790-ae2d59ff9661)

![image](https://github.com/user-attachments/assets/2036f512-581d-4ff5-b6ee-b78cd99036fd)

## Block diagram

![image](https://github.com/user-attachments/assets/5019b626-62c7-4185-ba83-11d744e5bb0b)

## Schematics
[Schematics](PT2399_DigitalEffectPedal.pdf) PDF can be found in the repository. 

![image](https://github.com/user-attachments/assets/09b07a00-c897-42f6-93b7-fe6db2b98f10)

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

## Tools

Tool used for schematics drwaing and pcb layout is [KiCad](https://www.kicad.org/), version 7.0.7

Tools used to draw block image is [ExcaliDraw](https://excalidraw.com/).
