# else-heart.break()
## Overview

Few basic codes for the game [else heart.break()](http://elseheartbreak.com/).

## Why I created this! (Contains Spoilers!)

- In-game Aniara OS v 3.5.0.1 doesn't get the job done, you need to configure every bit of the OS to make it work. Because of that I created a new OS in the game (hard to call it OS though) and there was a lot of computers and terminals in the Lodge Room so I wanted to use them for different things. First things first, you need to configure another total of 5 computers for this OS to work. Why? This way the code in the main computer is much more shorter, because you are connecting to another computer for every function / task. My main purpose was learning to call functions from another computer, so here it is. You can use any computer for the so called "main computer" except computers in the network field below.

## Configuring the files for the game

### RainOS - Creating a network (Contains Spoilers!)
```
var networkComputer1 = Connect("Lodge1_Room1_Computer8")
var networkComputer2 = Connect("Lodge_Room1_ComputerTerminalBoard1_ComputerTerminalBoard1_1")
var networkComputer3 = Connect("Fibonacci")
var networkComputer4 = Connect("Lodge_Room1_MediumSewerComputer_MediumSewerComputer_1")
var networkComputer5 = Connect("Lodge_Room1_PillarComputer_PillarComputer_1")
```
- All these computers are in the "Lodge Room". You need to add codes to these computers to make the main computer work without a problem. You can learn the computer names with "extractor" item.

## Purposes

### Add/Erase Data to Storage

- Nothing too fancy, it just a simple database program. You can add or erase data to database from the main computer but to show the values you need to use the database computer itself. (Useful when you are far away to Lodge Room and want to remember something later)

### Door Locker/Unlocker

- Simple code for locking / unlocking doors. Get the door name with "extractor" item.

### Bruteforce Door Unlocker

- Good to use when you want to learn to key code for the door you want to unlock but you need to watch it before the door unlocks. Also you can add this to any key and carry with you. TODO: When the door opens add key code to database.

### Trace Clearing Application

- If you don't want to leave any traces behind while hacking this program is just for you! You need to have the computer ID to connect and clear the trace from it though. (again, you can use the "extractor")

### Credit Card Account 

- Easily add money to your credit card account. No questions asked!

## Another Codes

### Screwdriver

- This modifies the screwdriver so when you use it on any computer it adds new functionalities to it!

### Upgraded Modifier

- Everybody probably figured this one out but I'll add it anyway. It modifies to Modifier so you can change the code of everything.

