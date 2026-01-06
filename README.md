# LoL Champion Skill Quiz (C)

## Result/Demo
🎬 Demo (YouTube): https://youtu.be/jMwWmPeBHlk

A console-based quiz game written in **C (Windows)**.  
The program shows **League of Legends champion skill descriptions** and asks the user to guess the champion name.  
It supports multiple difficulty modes and keeps a record of correct/incorrect answers.

## Features
- 3 difficulty modes:
  - **Easy**: shows Passive + Q/W/E/R
  - **Normal**: shows Q/W/E only
  - **Hard**: shows Passive only
- Select number of questions: **10 / 30 / 50**
- Randomized champion order each run (shuffle)
- Stores and prints results:
  - Correct list
  - Incorrect list (with the correct answer)
- Uses a simple **linked list** to store solved questions

## How it works
1. Choose difficulty (Easy/Normal/Hard)
2. Choose number of questions (10/30/50)
3. For each question, the program prints skill descriptions
4. User types the champion name (Korean name strings in this version)
5. At the end, the program prints:
   - all correctly answered champions
   - all incorrectly answered champions
