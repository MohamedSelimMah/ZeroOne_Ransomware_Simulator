# 🔐 Ransomware Simulator (For Educational Use Only) ⚠️
*A safe, hands-on tool to explore ransomware behavior — without real-world harm.*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Educational Use](https://img.shields.io/badge/Use-Educational-purple)](#️-important-disclaimers)

---

## 📌 About
This project simulates a **harmless ransomware attack** for **educational and research purposes**. It demonstrates file encryption techniques in a controlled, reversible, and fully transparent environment.  

> 💡 Designed for cybersecurity learners, ethical hackers, and teachers.

---

## 🚀 Features
- 🧮 Disguised as a simple calculator interface
- 🔐 Simulated file encryption (no actual data loss)
- 🗝️ Real-time decryption with key validation
- 💾 Secure local backups created automatically
- 📘 Transparent logging of all operations
- 🛑 Ethical warnings and non-malicious by design

---

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/ransomware-simulator.git
cd ransomware-simulator
pip install -r requirements.txt
```

> ✅ Python 3.8 or newer required

---

## 🖥️ How to Use

### 🔒 Simulate Encryption (via Calculator)
```bash
python main.py
```
1. Use the calculator as normal.
2. Upon exiting, choose files to "encrypt".
3. Encrypted versions are saved and backups stored in `Desktop/You_Got_Hacked`.

### 🔓 Decrypt Files
```bash
python decrypt.py
```
1. Enter the key shown during encryption.
2. Select files for restoration.
3. Files are recovered from safe backups.

---

## 📂 Project Structure

```
📦 ransomware-simulator/
├── 📜 main.py           → Calculator + encryption logic
├── 📜 decrypt.py        → Decryption tool
├── 📜 config.py         → Path and settings configuration
├── 📜 requirements.txt  → Python dependencies
└── 📂 test_files/       → Sample files to practice on
```

---

## 🛡️ Built-in Safety Features
- ✅ **Non-destructive**: Original files are backed up before any changes
- ✅ **No persistence**: No system or network alterations
- ✅ **No spreading**: No infection capabilities
- ✅ **Full transparency**: Logs and warnings included
- ✅ **Decryption included**: With proper key entry

---

## 🧪 Testing Guide
Sample files provided in `/test_files` to simulate attacks:
- 📄 `test_document.txt` — simple text file
- 🖼️ `test_image.jpg` — dummy image for testing

---

## ⚠️ Important Disclaimers
- 🧪 This is **strictly an educational tool**.
- ❌ Do **NOT** use it on systems without consent.
- 🔒 No real harm is done — **data is backed up**.
- 🧑‍⚖️ Misuse of this project is a violation of law and ethics.
- 📜 Review the [LICENSE](LICENSE) for usage terms.

---

## 📜 License
Licensed under the [MIT License](LICENSE).  
Please use responsibly and only in ethical, educational contexts.

---

## 🤝 Contributions & Feedback
Want to improve this project? PRs and ideas are welcome!  
If you have questions or suggestions, open an issue or discussion.

---

> 🧠 “Understanding threats is the first step to defending against them.”  
> — This simulator is a learning tool, not a weapon.
