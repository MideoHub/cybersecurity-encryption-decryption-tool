# Cybersecurity Encryption & Decryption Tool  🔓

<img src="src/assets/img_icon.jpeg" alt="Project Logo" width="60" height="70" >

A Python-based GUI application for demonstrating various classical encryption and decryption algorithms.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Supported Ciphers](#supported-ciphers)
- [File Handling](#file-handling)
- [Contributing](#contributing)

## Overview

The Cybersecurity Encryption & Decryption Tool is a Python-based graphical user interface (GUI) application designed to demonstrate various classical encryption and decryption algorithms. Built using Tkinter, this tool allows users to encrypt and decrypt text using ciphers such as Caesar Cipher, Playfair Cipher, Rail Fence Cipher, ROT13, Substitution Cipher, and Vigenère Cipher.

This project was developed as a learning exercise to explore cybersecurity concepts, specifically focusing on classical encryption techniques. It is intended for educational purposes and can serve as a foundation for further enhancements in cryptographic applications.

## Features

- **Multiple Ciphers**: Supports six classical ciphers:
  - Caesar Cipher
  - Playfair Cipher
  - Rail Fence Cipher
  - ROT13 Cipher
  - Substitution Cipher
  - Vigenère Cipher

- **User-Friendly GUI**:
  - Built with Tkinter
  - Main window to select a cipher
  - Individual windows for each cipher with input fields, key entry, and result display

- **File Handling**:
  - Upload text files to encrypt/decrypt
  - Download results as text files

- **Interactive Elements**:
  - Hover effects on buttons
  - Back button to return to the main menu

- **Error Handling**:
  - Displays error messages for invalid inputs

- **Modular Design**:
  - Code organized into separate modules for each cipher

## Prerequisites

Before running the application, ensure you have the following installed:

- Python 3.6+
- pip (Python package manager)
- Virtual Environment (optional but recommended)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MideoHub/cybersecurity-encryption-decryption-tool.git
   cd cybersecurity-encryption-decryption-tool 
   ```
 
2. Install dependencies:
   ```bash
    pip install -r requirements.txt
   ```
 
3. Run the application:

   ```bash
   python src/main.py
   ```

## Usage

1. **Launch the application**
2. **Select a cipher** from the main menu
3. **Enter your text** or upload a file
4. **Provide the required key** (if applicable)
5. Click **"Encrypt"** or **"Decrypt"**
6. **View the result** or download it as a file

## Supported Ciphers

### 1. Caesar Cipher
A substitution cipher where each letter is shifted by a fixed number down the alphabet.

### 2. Playfair Cipher  
A digraph substitution cipher that uses a 5×5 grid of letters for encryption.

### 3. Rail Fence Cipher  
A transposition cipher that writes the message in a zig-zag pattern down multiple rails.

### 4. ROT13 Cipher  
A special case of the Caesar cipher with a shift of 13 positions.

### 5. Substitution Cipher  
A cipher that replaces each letter with another letter from the alphabet.

### 6. Vigenère Cipher  
A method of encrypting alphabetic text by using a simple form of polyalphabetic substitution.

## File Handling

The application supports:
- Uploading text files for encryption/decryption
- Downloading results as text files


## Collaborator

[Mohamed Khiarey](https://github.com/khairy-nio)


## Contributing

Contributions are welcome!

-------------
#### Feel free to reach out with feedback or collaboration ideas!
