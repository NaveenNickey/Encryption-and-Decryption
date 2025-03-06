# Encryption and Decryption with Python (Using Fernet)
This project demonstrates how to perform encryption and decryption in Python using the Fernet module from the cryptography library. The code generates a key, encrypts a message, and decrypts it back to its original form.

# Features
- Encrypts plain text using the Fernet symmetric encryption algorithm.
- Decrypts the encrypted text to retrieve the original message.
- Secure key generation for encryption/decryption.

# Prerequisites
Ensure you have Python 3.x installed. This project requires the cryptography library.

# Key Management
The generated key must be securely stored and used for both encryption and decryption. Make sure to keep the key safe.

# How It Works
1. Key Generation: The Fernet.generate_key() method generates a random key used for both encryption and decryption.
2. Encryption: The encrypt() method encrypts the message, turning it into a byte string.
3. Decryption: The decrypt() method converts the encrypted byte string back into the original text.

# Contributing
If you have suggestions or improvements for this project, feel free to fork it and submit pull requests. Open issues for any bugs or feature requests.

# License
This project is licensed under the MIT License - see the LICENSE file for details.

