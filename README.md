# Attendance Requirement Calculator

A simple C program to help students calculate how many more classes they need to attend in each subject to meet the 75% attendance requirement. It takes the current date and attendance percentages and outputs how many sessions are still needed, assuming perfect attendance going forward.

---

## 📑 Table of Contents

- [Installation Instructions](#installation-instructions)  
- [Usage](#usage)  
- [Features](#features)  
- [Contributing](#contributing)  
- [License](#license)  
- [Acknowledgments](#acknowledgments)  
- [Contact Information](#contact-information)  

---

## 📥 Installation Instructions

### Prerequisites
- A C compiler (like GCC)
- A terminal or command prompt
- Basic knowledge of how to compile and run C programs

### Steps
1. Clone or download this repository.
2. Open your terminal in the project directory.
3. Compile the code using:
   ```bash
   gcc attendance_calculator.c -o attendance_calculator -lm
   ```
4. Run the compiled program:
   ```bash
   ./attendance_calculator
   ```

---

## 🚀 Usage

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

## ✨ Features

- Simulates total classes conducted from April 16 or May 1 to a selected date.
- Calculates required future classes for 8 different subjects.
- Uses a simple command-line interface.
- Helpful for students to manage attendance proactively.

---

## 🤝 Contributing

This was a solo project I (Rishik) did to learn more about C and how to apply logic to real-world student problems.  
If you're interested in contributing, feel free to fork the repo or suggest improvements.

> No CONTRIBUTING.md file exists yet — I'm still learning how to set up open-source contributions.

---

## 📄 License

This project doesn’t have an official license yet.  
Feel free to use it for learning or improve upon it for personal or academic use.

---

## 🙏 Acknowledgments

- **Myself (Rishik)** – for building and debugging this code 😅  
- The **C Programming Language** – for teaching me patience  
- **Online references and class notes** – used for understanding logic and subject schedules  
- No external libraries or frameworks were used — just standard C and `<math.h>`

---

## 📬 Contact Information

**Name:** Rishik  
**Email:** *(you can add it if you want)*  
**GitHub:** *(add your profile link if available)*
