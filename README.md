# Cryptography
# Password Strength Analyzer (Jupyter Notebook)

## Overview
This project is a **Password Strength Analyzer** implemented in a Jupyter Notebook.  
It evaluates the robustness of user-entered passwords using **entropy calculations** and estimates how long they would take to crack via **brute-force attacks**.  
The notebook also provides **inline visualization** with color-coded charts for better understanding.

---

## Features
- Detects **weak/common passwords** using a dictionary check.
- Calculates **entropy** based on character diversity and length.
- Estimates **brute-force cracking time** (assuming 1 billion guesses/sec).
- Classifies passwords as **Weak, Moderate, Strong, Very Strong**.
- Provides **inline visualization** using Matplotlib.

---

## Tech Stack
- **Language:** Python 3
- **Environment:** Jupyter Notebook
- **Libraries:** 
  - `math` (entropy calculation)
  - `re` (regex for character set detection)
  - `matplotlib` (visualization)

---

## Installation
1. Install Jupyter Notebook (if not already installed):
   ```bash
   pip install notebook
