# passphrase-cracking-calculator
This is a Password vs Passphrase Entropy calculator used to estimate how long it takes for a passphrase to be cracked or compromised even in the age of AI.  The calculator uses standard information theory equations to determine security strength. 

A lightweight, interactive visualizer built for **Cybersecurity Awareness Month**. This tool demonstrates the mathematical advantage of using multi-word passphrases over traditional complex passwords.

## Purpose
This project is part of a 4-week cybersecurity habit-building series. Week 1 focuses on password hygiene, emphasizing that **length defeats complexity**. By visualizing the entropy (bits) and estimated time-to-crack, this tool helps users intuitively understand why a 4-word passphrase is exponentially stronger than a traditional 8-character password packed with symbols.

#DontMakeItEasyForThem

## Features
* **Real-Time Entropy Calculation:** Adjust sliders to see how length and character sets impact mathematical security instantly.
* **AI-Era Cracking Estimates:** Calculates time-to-crack assuming a modern automated hardware rig guessing at a rate of 100 billion combinations per second.
* **Diceware Math:** Passphrase entropy is based on the standard 7,776-word Diceware dictionary pool.
* **Zero Dependencies:** A single, self-contained HTML file utilizing vanilla HTML, CSS, and JavaScript. No npm, webpack, or build tools required.
* **Responsive Design:** Mobile-friendly CSS grid layout that looks great on desktop and mobile browsers.

## 🚀 Getting Started

### Run Locally
Since this is a self-contained file, running it is instantaneous:
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/entropy-calculator.git](https://github.com/yourusername/entropy-calculator.git)
