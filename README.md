📌 Overview

This project implements a Scalar Crypto Extension for 32-bit RISC-V architecture, focusing on secure and efficient AES-128 encryption and decryption. The system was developed on the ESP32C3 (RISC-V-based) microcontroller and integrates both hardware and software components to demonstrate real-time cryptographic processing.

The project bridges gaps in existing RISC-V cryptographic research by offering a standardized, scalable, and resource-efficient AES extension suitable for lightweight embedded devices.

🔍 Key Features

⚙️ AES-128 encryption & decryption implemented for RISC-V architecture

🔐 Hardware–software integrated crypto pipeline using ESP32C3

🧮 Real-time user interaction via LCD (I2C) and 4×4 keypad

🌐 Web-based interface for file encryption/decryption using AES-128

📊 Hardware timing validation (≈ 3.94 ns execution time)

🧪 Software unit testing for encryption/decryption accuracy

🏆 Presented at SSUET Research Symposium — Secured 2nd Position

🛠️ Tech Stack & Tools

RISC-V ISA (32-bit)

ESP32C3 microcontroller

AES-128 algorithm

C / C++ for embedded programming

PHP for web-based crypto interface

LCD (I2C), 4×4 Keypad

ISim Simulator for clock diagram analysis

🧩 System Architecture
Hardware Pipeline

User inputs plaintext/key via keypad

Encryption/Decryption on ESP32C3

Output displayed on 16×2 LCD

Timing validated using clock analysis

Web Interface

Upload file → enter AES key → encrypt/decrypt

Implemented using PHP + AES libraries

Supports text-based secure file processing
