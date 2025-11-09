# 🔐 Caesar Cipher in Python

A simple encryption and decryption program built with Python.  
It uses the **Caesar Cipher algorithm**, which shifts each letter by a fixed number in the alphabet.  
This was one of my early exercises from [freeCodeCamp](https://www.freecodecamp.org/) to learn string manipulation and function design.

---

## 🧠 What I Learned
- How to **slice and concatenate strings** (`alphabet[shift:] + alphabet[:shift]`)
- How to use **`str.maketrans()`** and **`.translate()`** for character mapping  
- How to design **reusable functions** (`encrypt()` / `decrypt()`)
- How to handle **uppercase and lowercase** letters properly  
- The concept of **encryption / decryption logic**

---

## 💻 Example Usage

```python
from caesar_cipher import encrypt, decrypt

message = "Hello World"
shift = 5

encrypted = encrypt(message, shift)
print(encrypted)   # Mjqqt Btwqi

decrypted = decrypt(encrypted, shift)
print(decrypted)   # Hello World

```

## 🚀 Future Improvements
- Add number and punctuation support
- Build a simple GUI version using Tkinter
- Add command-line interface (CLI) support with argparse

## ✨ Author
 **RAKUzzz**  
 This project is part of my Python learning journey toward becoming a Software Engineer.
