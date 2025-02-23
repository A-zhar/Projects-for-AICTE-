# Secure Data Hiding in Images using Steganography

Secure Data Hiding in Images using Steganography
Project Overview
This project implements image-based steganography that allows users to securely hide and retrieve secret messages inside an image using a password. The image processing is handled with OpenCV, and the script is written in Python.

Features
Encrypt a Secret Message: Hide a message inside an image without changing its appearance. Protect the message with a password.

Decrypt the Message: Extract the hidden message from the image. Requires the correct password for successful decryption.

Simple Command-Line Interface: Easy-to-use command-line interface for encryption and decryption.

Project Structure
encrypt_image.py: Script for encrypting messages in an image.

decrypt_image.py: Script for decrypting messages from an image.

README.md: Project documentation.

Installation & Setup
Install Dependencies: Make sure you have Python 3.6+ installed. Then, install the required libraries:

bash
pip install opencv-python
Run the Encryption Script: To encrypt a message into an image:

bash
python encrypt_image.py
Select an image.

Enter a secret message.

Enter a password.

Save the encrypted image.

Run the Decryption Script: To decrypt a message from an image:

bash
python decrypt_image.py
Select the encrypted image.

Enter the correct password.

Retrieve the hidden message.

Usage
Encrypting a Message:

Select an image file.

Enter your secret message.

Enter a password for protection.

Click Encrypt → Save the encrypted image.

Decrypting a Message:

Select the encrypted image file.

Enter the correct password.

Click Decrypt → The message is displayed.

Security Considerations
The message is hidden at the pixel level but is not strongly encrypted. For added security, use additional cryptographic encryption (e.g., AES) before encoding.

If the password is incorrect, decryption will fail.

Future Enhancements
Support for multiple image formats (JPEG, PNG, etc.).

Stronger encryption methods for added security.

Mobile app version using Python-Kivy or Flutter.

Credits
Developed using:

Python 🐍

OpenCV 📷


## Contributors
- **Khaja Azharuddin
- **Channabasava Yadav & Vignesh M (Edunet)** – Mentors

## Acknowledgment
Special thanks to **Channabasava Yadav and Vignesh M from Edunet** for their guidance and mentorship in completing this project.

## Contact
For any queries or suggestions, contact:
- **GitHub**:https://github.com/A-zhar/steganography-cybersecuirty-project
- **Email**: khajaazharuddin312@gmail.com
