# Password-Manager
A Project on Cyber sercurity - The Passwaord Manager
 🔐 Password Manager – Secure Offline Credential Vault

A secure, offline password manager application built using **Python**, **Tkinter**, **SQLite**, and **AES encryption**. This tool allows users to store, manage, and retrieve credentials with a strong focus on privacy and usability.

---

## 🧠 Project Overview

This project was created to solve a common security problem: password reuse and insecure storage. Unlike cloud-based managers, this application runs entirely offline, giving users **full control** over their encrypted data.
You can view the complete Software Requirements Specification (SRS) and implementation details in the PDF linked below:
https://drive.google.com/file/d/1w4x0A-WBPufgBeFgvLiH0kOySnAP__D3/view?usp=sharing

---

## 📌 Features

- 🔑 **Master Password Authentication** using SHA-256 hashed key
- 🔒 **AES-256 Encryption (CBC mode)** for all credentials
- 🧩 **CRUD Operations**: Add, View, Update, and Delete records
- 📋 **Clipboard Integration**: Securely copy passwords temporarily
- 🔍 **Search Functionality** by website or username
- 🎨 **Tkinter GUI** with color-coded buttons and intuitive layout
- 💾 **Local SQLite Database** – no internet required
- ☁️ **(Planned)**: Password Generator, 2FA, Cloud Sync, Biometric Login

---

## 🖼️ UI Preview

![Password Manager](https://github.com/user-attachments/assets/0b7ac461-5492-4807-96ba-20cf67d461b3)

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.x | Core programming language |
| Tkinter | GUI development |
| PyCryptodome | AES Encryption & Crypto utilities |
| SQLite3 | Lightweight local database |
| hashlib | Master key derivation using SHA-256 |

---

## 💻 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/password-manager.git
   cd password-manager

2. Install dependencies:
   ```bash
    pip install pycryptodome
3. Run the application:
   ```bash  
      python main.py

---

## 🔐 Security Notes
Master password is never stored – it's required each session to decrypt data.

Passwords are stored encrypted using AES (CBC) with a randomly generated IV.

This application does not require internet access, reducing exposure to external threats.

---

## 🚀 Future Enhancements
✅ Password strength analyzer & generator

✅ Two-Factor Authentication (2FA)

✅ AWS cloud backup and sync

✅ Browser extension for autofill

✅ Role-based access for enterprise

---

## 📜 License

This project is open-source and free to use for learning or demo purposes.

---

## 👏 Credits

Made with ❤️ by **Shakya**  
