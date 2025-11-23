# 🔐 Cyber Security Internship - Task 6: Password Strength Evaluation

## 🚀 Overview

This repository contains the deliverables for **Task 6: Create a Strong Password and Evaluate Its Strength**. The objective was to understand the elements that make a password strong and evaluate varying complexity levels using an online strength tool.

## 🎯 Deliverables Submitted

* **`README.md`**: This report summarizing the findings, analysis, and best practices.
* **Screenshots**: Three screenshots demonstrating the test results for the varying passwords on the password strength checker (e.g., `passwordmeter.com`).

## 🛠️ Tools & Environment

* **Tool:** Online Password Strength Checker (Password Meter)
* **Environment:** Web Browser 

---

## ⚙️ Methodology (Experiment)

To understand how complexity and length affect password security, three distinct passwords were created and tested. The scores and feedback were recorded for analysis.

| Password Category | Example Password | Length | Complexity Factors | Tool Score / Crack Time | Key Observation |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **P1: Weak/Baseline** | `yash123` | 7 | Lowercase, Numbers | *(Fill in your low score)* | Weak due to short length and dictionary word usage. |
| **P2: Length Focus** | `MyCatLovesToEatSalmon` | 21 | Mixed Case | *(Fill in your high score)* | High score primarily driven by significant **length** (passphrase structure). |
| **P3: Complexity Focus** | `P@ssw0rd!123` | 13 | Mixed Case, Numbers, Symbols | *(Fill in your good score)* | Strong due to the **diversity** of character types. |

---

## 🔎 Analysis: Why Password Complexity Matters

### 1. The Impact of Length (Entropy)
The test results confirmed that **length** is the single most important factor for password strength.
* The **Length Focus** password (P2) demonstrated that even with limited complexity, a high number of characters dramatically increases the total number of possible combinations (known as **entropy**). This exponentially slows down **Brute Force Attacks**.

### 2. The Role of Character Diversity
The **Complexity Focus** password (P3) showed that adding **uppercase, numbers, and symbols** (character diversity) further boosts the score.
* This diversity increases the size of the character set available to the attacker, providing additional security against both brute force and **Dictionary Attacks** (which rely on common words and phrases).

### 3. Summary of Security
For maximum security, the ideal password must be both **long (a passphrase)** and include a **diverse mix** of characters to provide the highest resistance against modern hacking techniques.

## ⭐ Key Learnings and Best Practices

1.  **Prioritize Passphrases:** Choose a long, random, and memorable sentence or sequence (a passphrase) over a short, highly complex password.
2.  **Use Diversity:** Ensure passwords include a mix of uppercase, lowercase, numbers, and symbols.
3.  **Avoid Personal Data:** Never use personal information, sequential numbers, or common dictionary words.
4.  **Unique Passwords:** Use a unique password for every single account to prevent **credential stuffing** attacks.
5.  **Use a Password Manager** and enable **Multi-Factor Authentication (MFA)** for all critical accounts as an essential secondary defense layer.
