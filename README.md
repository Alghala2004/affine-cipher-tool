# 🔐 Affine Cipher GUI (Python + Tkinter)

## 📋 Overview

This project is a simple Graphical User Interface (GUI) application that demonstrates the Affine Cipher encryption and decryption technique using Python and Tkinter.

It allows users to input text, provide keys, and perform encryption/decryption in an interactive way.

---

## ✨ Features

- 🔒 Encrypt plaintext using Affine Cipher  
- 🔓 Decrypt ciphertext back to original text  
- 🧮 Custom keys (a, b) input  
- ⚠️ Error handling for invalid keys  
- 🖥️ Simple and user-friendly GUI  
- 🔤 Automatic uppercase conversion  

---

## 🧠 What is Affine Cipher?

Encryption:
E(x) = (ax + b) mod 26

Decryption:
D(x) = a⁻¹(x - b) mod 26

Where:
- a and b are keys  
- a⁻¹ is the modular inverse of a modulo 26  
- gcd(a, 26) = 1  

---

## 🛠️ Technologies Used

- Python 🐍  
- Tkinter  

---

## 🚀 How to Run

### 1️⃣ Install Python
Make sure Python is installed (version 3.x recommended)

### 2️⃣ Run the Script
```bash
python affine_cipher_gui.py
```

---

## 💻 How to Use

### 🔐 Encryption
1. Enter plaintext  
2. Enter key values (a, b)  
3. Click Encrypt  
4. Ciphertext will appear  

---

### 🔓 Decryption
1. Enter ciphertext  
2. Enter the same keys  
3. Click Decrypt  
4. Original plaintext will appear  

---

## ⚠️ Important Notes

- The key a must satisfy gcd(a, 26) = 1  
- Only uppercase A–Z are handled correctly  
- Spaces are preserved  

---

## 📁 Project Structure

affine-cipher-gui/
│
├── affine_cipher_gui.py
└── README.md

---

## 🔒 Security Note

This project is for educational purposes only. Affine Cipher is not secure for real-world use.

---

## 👨‍💻 Author

Developed as a simple cryptography learning tool.
