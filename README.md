# 🔐 Friendly Password Generator

![Python Version](https://img.shields.io/badge/python-3.10%2B-blue)
![Status](https://img.shields.io/badge/status-completed-brightgreen)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Development](#development)
- [Contact](#contact)

## Overview
Friendly Password Generator is a secure and simple terminal-based Python application created as the second task of the CodSoft Python Internship program. It is designed to help users generate strong, random, and reliable passwords based on best security practices, with guaranteed inclusion of lowercase, uppercase, digits, and special characters.

## Features
- **Secure Password Generation**
  - Ensures at least one uppercase, lowercase, digit, and special character
  - Password length validation (minimum 4 characters)
  - Fully randomized password output
- **User-Friendly Design**
  - Simple and interactive CLI prompts
  - Graceful error handling for invalid input
  - Clear feedback with generated password display
- **Lightweight and Efficient**
  - No external dependencies
  - Memory-efficient design
  - Fast and reliable for repeated use

## Installation
### Requirements
- Python 3.10 or newer

### Quick Start
```bash
# Clone the repository
git clone https://github.com/your-username/friendly-password-generator.git

# Navigate to the project directory
cd friendly-password-generator

# Run the application
python password_generator.py
```

## Usage
Once the script is running, follow the prompt to input the desired password length:

```text
PASSWORD GENERATOR
------------------
Enter the desired password length (minimum 4): 12

Generated Password: @1KzLp#8gqW!
```

## Development
### Project Structure
```
friendly-password-generator/
├── password_generator.py   # Core logic for password generation
├── README.md               # Documentation file
└── LICENSE                 # License file (optional)
```

### Implementation Details
- Defined character sets: lowercase, uppercase, digits, and symbols
- Combined pool for random character selection
- Password constructed with one from each category + random fill
- `random.shuffle()` for secure arrangement
- Pure Python implementation using built-in `random` module

## Contact
**Akash Karn**  
[![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/akashkarn9486)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/akash-karn-851875255)  

---

Developed during the Python Internship Program at CodSoft  
Project Repository: https://github.com/your-username/friendly-password-generator.git
