# Description
This project is a calculator that can perform advanced operations. To run a calculation, first type a command,
then type in two different numbers to perform a calculaton. This takes Module 5's caluclator and adds additional
operations, unit tests, and the colorama library to help.
The full list of actions is listed on the "Commands section".

# Installation
1. Download Python on your computer
2. Set up virtual environment using "python -m venv venv"
3. Activate virtual environment by typing "source venv/bin/activate"
4. Install necessary dependencies using "pip install -r requirements.txt
5. Install colorama with "pip install colorama"

# Calculator Commands
add- adds two numbers together
subtract- subtracts the first number from the second number
multiply- multiplies two numbers together
divide- divides the first number by the second number
power- raises the first number to the power of the second number
root- finds the 2nd number root of the first number
modulus- divides the first number by the second number and returns the remainder
int_divide- divides the first number by the second number and drops remainder leaving just the whole number
percent- divides the first number by the second number and multiplies the quotient by 100
abs_diff- finds the absolute value of the difference between two numbers

help- loads list of valid commands
history- shows history of calculations
clear- empties calculation history
undo- undoes the last calculation
redo- redoes the last undone calculation
save- saves calculation history to a file
load- loads calculation history from a file
exit- exits program

# Setting up .env file

All environment configurations are optional. Here are what each one does. 

CALCULATOR_LOG_DIR: Creates directory for log files. 
CALCULATOR_HISTORY_DIR: Creates Directory for history files.
CALCULATOR_MAX_HISTORY_SIZE: Limits number of history entries.
CALCULATOR_AUTO_SAVE: Enables auto-save of history (true or false).
CALCULATOR_PRECISION: Maximum of decimal places for calculations.
CALCULATOR_MAX_INPUT_VALUE: Largest allowed input value.
CALCULATOR_DEFAULT_ENCODING: Default encoding for file operations.

# Setting up
Uses latest stable versions of checkout and setup python.
.github/workflows python-app.yml file installs pip on github and runs a coverage test of 90% or better to pass. 