# PLP Python Week 8 - Personal Toolkit

## Project Description

This project is a menu-driven Python toolkit containing four useful tools:

1. **Simple Calculator** - Performs addition, subtraction, multiplication, and division.
2. **To-Do List** - Allows users to add, view, and remove tasks.
3. **Number Guessing Game** - Gives the user five chances to guess a secret number.
4. **Name Formatter** - Formats a person's name and displays information about it.

The program uses a menu loop that continues running until the user selects the Quit option.

## Files

- `toolkit.py` - Contains the complete Python program.
- `toolkit_plan.txt` - Contains the project plan and programming concepts.
- `screenshots/` - Contains screenshots showing the menu and each tool working.
- `README.md` - Contains project information and reflection.

## How to Run

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Run the following command:

```bash
python toolkit.py
```

4. Choose an option from the menu.
5. Follow the instructions displayed by the program.
6. Select option 5 when you want to quit.

## Python Concepts Used

The project demonstrates:

- Variables
- User input
- `if`, `elif`, and `else`
- `while` loops
- `for` loops
- Lists
- `append()`
- `pop()`
- Functions
- `try` and `except`
- String methods
- f-strings

## Reflection

The hardest part of this project was connecting all the individual tools to one main menu loop. I had to make sure that each tool returned to the main menu instead of ending the whole program. One of the bugs that took the longest to fix was handling invalid user input without allowing the program to crash. I solved this by using `try` and `except` around inputs that require numbers. I also learned how useful lists are for storing information that changes while a program is running. The to-do list helped me understand how `append()` and `pop()` can change a list. If I had one more week, I would add more tools and save the user's to-do list to a file so that the tasks would still be available after restarting the program.
