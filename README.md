# Attendance Requirement Calculator

A simple C program to help students calculate how many more classes they need to attend in each subject to meet the 75% attendance requirement. It takes the current date and attendance percentages and outputs how many sessions are still needed, assuming perfect attendance going forward.

---

## Table of Contents

- [Installation Instructions](#installation-instructions)  
- [Usage](#usage)  
- [Features](#features)
  
---

## Installation Instructions

### Prerequisites
- A C compiler (like GCC)
- A terminal or command prompt
- Basic knowledge of how to compile and run C programs

### Steps
step 1: Clone or download this repository.
step 2: Open your terminal in the project directory.
step 3: Compile the code using:
   ```bash
   gcc attendance_calculator.c -o attendance_calculator
   ```
step 4: Run the compiled program:
   ```bash
   ./attendance_calculator
   ```

---

## Usage

1. Run the program in your terminal.
2. Enter the **day and month number** when prompted (only April and May are considered).
3. Enter your **current attendance percentage** (0–100) for each subject.
4. The program will tell you how many **more classes you need to attend** for each subject to reach 75%.

### Example

```bash
enter day number: 5
enter month number: 5
enter the attendance percentage of all subjects:
1.EM: 60
2.AP: 72
...
```

**Output:**
```
1.aptt = 2.00
2.ap = 1.25
3.em = 3.80
...
```

---

## Features

- Simulates total classes conducted from April 16 or May 1 to a selected date.
- Calculates required future classes for 8 different subjects.
- Uses a simple command-line interface.
- Helpful for students to manage attendance proactively.


