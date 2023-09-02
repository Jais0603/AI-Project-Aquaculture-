# Aquaculture Technology

This README provides an overview of the Java code for "AquacultureTechnology," a program that simulates an aquaculture system. The program monitors and controls the hunger levels of shrimp and fish, adjusting food dispensers accordingly.

## Table of Contents

- [Introduction](#introduction)
- [How It Works](#how-it-works)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

AquacultureTechnology is a Java program designed to manage the feeding of shrimp and fish in an aquaculture system. The program allows users to input hunger levels for both shrimp and fish, and it calculates the appropriate food dispenser settings based on those hunger levels.

## How It Works

The program follows these steps:

1. **Initialization**: Upon execution, the program initializes hunger levels for shrimp and fish, as well as food dispensers. It also creates a scanner for user input.

2. **Detect Hunger Levels**: The program prompts the user to input hunger levels for shrimp and fish on a scale of 0 to 100.

3. **Control Food Dispensers**: Based on the detected hunger levels, the program calculates the appropriate food dispenser settings for both shrimp and fish. The logic is as follows:
   - If hunger level is less than 50, the food dispenser is set to 0%.
   - If hunger level is between 50 and 75, the food dispenser is set to 25% (shrimp) or 50% (fish).
   - If hunger level is 75 or higher, the food dispenser is set to 50% (shrimp) or 100% (fish).

4. **Display Results**: The program prints the food dispenser settings for shrimp and fish to the console.

## Usage

To use the AquacultureTechnology program, follow these steps:

1. **Compile**: Compile the Java code using a Java compiler.

2. **Run**: Run the compiled program.

3. **Input Hunger Levels**: When prompted, input the hunger levels for shrimp and fish as per the program's instructions.

4. **View Food Dispenser Settings**: The program will calculate and display the food dispenser settings for both shrimp and fish based on the input hunger levels.

## Contributing

Contributions to this project are welcome. If you'd like to contribute, please follow these steps:

1. Fork this repository to your own GitHub account.

2. Create a new branch to work on your improvements.

3. Make your changes, test them thoroughly, and ensure the code remains well-documented.

4. Submit a pull request to the original repository, explaining the changes you've made and why they are valuable.


Enjoy using AquacultureTechnology to manage your aquaculture system's food dispensers!

