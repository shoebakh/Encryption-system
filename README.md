# Encryption-system

# 🔐 Python Encryption System

A simple yet fun **Encryption System** written in Python that demonstrates different classical ciphers. This project provides a menu-driven CLI interface allowing the user to encrypt any sentence using various techniques.

## 💡 Features

- **Caesar Cipher**: Shift characters by a specified amount.
- **Vowel Substitution Cipher**: Replace vowels with random digits.
- **Atbash Cipher**: Mirror characters across the alphabet.
- **ROT13 Cipher**: Rotate characters by 13 positions (a subset of Caesar).
- **Combo Mode**: Applies Caesar → Atbash → ROT13 → Vowel Substitution in sequence for layered encryption.

---

## 📋 Menu Options

MENU:

# Caesar Cipher Encryption

# Vowel Substitution Cipher

# Atbash Cipher

# ROT13 Cipher

# Combine Everything!!!

 
## 🚀 Getting Started

### Requirements

- Python 3.6+

### Running the Script

1. Save the code as `encryption_system.py`.
2. Run the script:

```bash
python encryption_system.py
```

# Follow the prompts to choose the encryption method and enter the text.
# EXAMPLE:-
MENU:
1. Caesar Cipher Encryption
2. Vowel Substitution Cipher
3. Atbash Cipher
4. ROT13 Cipher
5. Combine Everything!!!

Enter your encryption choice: 1
Enter the sentence for encryption: Hello World!
Specify shift: 3
Khoor Zruog!

### 📦 File Structure
encryption_system.py     # Main Python script with encryption logic
README.md                # Project documentation

# 🛠️ Implementation Highlights

Uses match-case (Python 3.10+) for cleaner control flow
string module for character operations
random module to generate digit substitutions for vowels
Modular functions for easy extension and reuse


