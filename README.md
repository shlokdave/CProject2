# Formatter Program

## Description
- This project is a C-based program that is designed to format personal data, including names, dates, and social security numbers. The program reads input data from text files and outputs the formatted data. The project is modular in design, with having separate components handling different types of data. This type of design helps ensure flexibility and maintainbility.

## Features
- Modular Design: Program is divided into multiple components: 
- Name Module: Processes and formats names according to specific formatting rules.
- Date Module: Handles parsing, validation, and formatting of dates.
- SSN Module: Manages validation and formatting of social security numbers.
- Utility Module: Provides general-purpose functions to use across the entire program.
- Comprehensive Testing: Robust testing framework is included as it automatically compiles the program and runs a series of pre-defined test cases to validate output against expected results. 
- Error Handling: The program includes checks to ensure input data is correctly formatted and handles across the program gracefully.

## Installation
- Ensure you have a C compiler (such as "gcc") installed on your system.
- Clone the repository: git clone https://github.com/shlokdave/CProject2.git
- Enter the command: cd CProject2
- Compile the project using the provided 'test.sh' script

## Testing
- After compiling the program, the input files can be ran containing the data to be processed
- Example: ./formatter < namelist-01.txt > output.txt
- The program reads the input data, processes it, and then outputs the formatted data to 'output.txt'.
