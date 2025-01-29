# Coin Insertion Program

## Overview
This program simulates a coin insertion system where the user inserts coins into a machine to reach a total of 50 cents. The user is prompted to input coin values (5, 10, or 25 cents). The program keeps track of the total amount inserted and provides feedback about how much more is needed or the change owed once the total reaches or exceeds 50 cents.

## Features
- The user is prompted to insert coins of values 5, 10, or 25 cents.
- The program keeps a running total of the inserted coins.
- After each coin insertion:
  - If the total is less than 50, the program shows how much more is needed.
  - If the total reaches or exceeds 50, the program displays the change owed.
- Invalid coins (values not equal to 5, 10, or 25) prompt the program to remind the user of the required amount.

## Example Usage
```
$ python coin_insertion.py
Insert Coin: 10
Amount Due: 40
Insert Coin: 25
Amount Due: 15
Insert Coin: 5
Amount Due: 10
Insert Coin: 25
Change Owed: 5
```

## How to Run
1. Run the program by executing:
   ```
   python coin_insertion.py
   ```
2. Insert coins by inputting valid coin values: 5, 10, or 25.
3. The program will calculate and display the remaining amount due or the change owed after each coin insertion.

## Notes
- The program ensures only valid coins are accepted (5, 10, or 25 cents).
- The process repeats until the total reaches or exceeds 50 cents, at which point change is returned if necessary.
