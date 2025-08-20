# security-cipher-encryption-decryption
This repository contains a simple encryption and decryption system implemented in Python using modular arithmetic. The cipher operates by mapping characters to numbers, performing encryption and decryption using a key, and checking the validity of the ciphertext and plaintext.

# Security Cipher - Encryption and Decryption

## Overview
This project demonstrates a simple encryption and decryption system using a **modular cipher** algorithm. It uses a fixed-length key to encrypt and decrypt messages (only capital letters). The encryption is done by adding the corresponding characters' values, while decryption is done by subtracting them. 

The notebook allows users to:
- **Encrypt** a message using a key.
- **Decrypt** the ciphertext using the same key.
- Check if the **decrypted message matches** the original plaintext.

## Features
- **Encryption**: Encrypts plaintext by adding the values of the corresponding characters in the key and the message.
- **Decryption**: Decrypts ciphertext by subtracting the values of the corresponding characters in the key and the ciphertext.
- **Input Handling**: User-friendly input prompts for both plaintext and ciphertext.
- **Key Validation**: Ensures that the key is long enough for encryption and decryption.

## Technologies Used
- **Python**: The entire logic is implemented in Python.
- **Jupyter Notebook**: The notebook allows interactive execution of encryption and decryption functions.

## Example Usage
1. Enter the plaintext: `HELLO`
2. Enter the key: `THISISANEXAMPLEKEY`
3. The notebook will display the corresponding ciphertext.
4. Enter the ciphertext to decrypt and verify the correctness.

## Project Structure
- **midterm_security.ipynb**: The Jupyter Notebook that contains the code for encryption and decryption, along with the interactive user input.
- **CM2025 security part B.pdf**: A reference document related to the security topic.

