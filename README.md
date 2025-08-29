# Spectra v2.0 – Security Toolkit

**Professional Penetration Testing & Bug Bounty Framework**  
Developed by musabakif, 2025

---

## ⚡ Purpose
Spectra is an **educational and professional security toolkit** for penetration testing and bug bounty automation.  
It is designed to:  
- Test web applications for vulnerabilities  
- Test social media and password security  
- Automate wordlist generation and brute force operations  

> **Note:** This tool is for **educational purposes only**. Unauthorized use on real systems is illegal.

---

## 🛠️ Features

- Web testing: `sqlmap`, `nuclei`, `xsstrike`, `nikto`, `nmap`, `dirsearch`  
- Social media / brute force testing: `hydra`, `john`  
- Wordlist generation: `cewl`, `crunch`  
- Multi-threaded parallel execution (web + social media)  
- Color-coded CLI and central red banner  
- Timestamped logs for all operations  
- Optional personal log directory  
- Final report can be generated in **TXT/HTML/PDF** format  
- Automatic tool and dependency check (self-check)  
- Compatible with Termux, Linux, macOS (Windows requires manual setup)

---

## 📥 Installation

1. Make sure Git and Python 3 are installed:  
   ```bash
   # Termux
   pkg install git python
   # Linux
   sudo apt install git python3 python3-pip
   # macOS
   brew install git python

2. Clone the repository:

git clone https://github.com/musabakif/Spectra.git
cd Spectra


3. Run the script to install missing tools if needed:

python3 spectra.py




---

⚙️ Usage

1. Run the script:

python3 spectra.py


2. Choose an option from the menu:

[1] Web Test

[2] Social Media / Brute Force Test

[3] Wordlist Generation

[4] Install Missing Tools

[0] Exit



3. Optionally, create a personal log folder for user-specific logs.


4. All outputs are logged automatically, and a final report is generated.




---

🔒 Caution

This tool is for educational/testing purposes only. Unauthorized usage is illegal.

On Windows, some tools require manual installation.

Automatic installation is fully supported on Termux/Linux/macOS.
