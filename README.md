<h1>Ransomware Implementation Using Python Cryptography Libraries</h1>
##Introduction
Ransomware is a malicious software or code that is used to infect or attack victim by encrypting the data and demand for ransom to decrypt the data. we have used python to create our encryption executable file that can encrypt data in a specified directory. We have used fernet library to generate encryptio key to encrypt data.
## Directory Structure

```
ComputerSecurity/
├── Codes/
│ ├── Encryption_code.py # Script for encrypting files
│ └── Ransom_Detectioncode.py # Script to detect ransomware activities
├── Linux/
│ ├── Ransomware_Executable/
│ │ ├── Build # Build directory for compilation artifacts
│ │ ├── Dist/
│ │ │ └── Encryption_code # Compiled executable for Linux
│ │ └── Encryption_code.spec # Spec file for PyInstaller or similar tools
└── Windows/
├── Ransomware_Executable/
│ ├── Build # Build directory for compilation artifacts
│ ├── Dist/
│ │ └── Encryption_code # Compiled executable for Windows
│ └── Encryption_code.spec # Spec file for PyInstaller or similar tools
