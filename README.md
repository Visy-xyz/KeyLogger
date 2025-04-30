# 🔐 Python KeyLogger (For Educational Use Only)

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Platform](https://img.shields.io/badge/platform-Windows/Linux-lightgrey)
![Status](https://img.shields.io/badge/status-educational-red)
![Security](https://img.shields.io/badge/warning-ethical%20use%20only-critical)

> ⚠️ **Disclaimer**: This project is for **ethical hacking, security research**, and **educational demonstrations** only. Do **not** use this code to target or spy on others without their explicit consent. Unauthorized use is **illegal** and against GitHub's policy.

---

## 💡 What Is This?

This project is a **Python-based KeyLogger** that silently captures keyboard input from a target machine and periodically sends the logs to a designated email address using SMTP.

Once executed on a system, the KeyLogger operates in the background, saving keystrokes and exfiltrating the data after a specified threshold.

---

## 📂 Folder Structure

KeyLogger/ │ ├── keylogger.py # 🔑 The main script – records keystrokes and sends email ├── README.md # 📘 You're reading it! └── (Optionally) build/ # 📦 Use pyinstaller to build an executable


---

## ⚙️ Features

- 🎯 **Real-time keystroke logging**
- 📩 **Automatic email sending** (after 100+ characters)
- 👻 **Silent background operation**
- 🔐 **Gmail SMTP integration**
- 🧪 Great for lab testing and security workshops

---

## 🚀 How to Use

> 💻 You must have Python installed. Recommend Python 3.8+

1. **Clone this repo** or download the `keylogger.py` file:

2.Install the required package:
pip install pynput

3.Edit the script
Open keylogger.py and set:

Your sender Gmail address
Receiver Gmail (can be same)
App password (generate it from Google App Passwords)

4.Run it:
python keylogger.py

5.✅ Logs will be emailed to you after every 100 keystrokes.

🛠 Convert to Executable (Optional)
To run without a console window:

pip install pyinstaller
pyinstaller --noconsole --onefile keylogger.py
Your .exe file will appear in the dist/ folder.

📹 Tutorials
Want to learn how it works?
👉 YouTube: How Keyloggers Work

Or…

📞 Contact Me
Need help setting it up or customizing it?

🧠 Educational Use Cases
Cybersecurity training

Ethical hacking labs

Security awareness simulations

Python reverse engineering

❌ Legal Notice
This software is not intended for use in unauthorized surveillance, spying, or data theft. Misuse can result in legal consequences. Always use in controlled environments with permission.

© 2025 • Built with 🧠 and ☕ by [Visy-xyz]




