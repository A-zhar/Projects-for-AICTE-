# Secure Data Hiding in Images using Steganography

## Overview
This project implements an image-based steganography technique to securely hide and retrieve messages within digital images. It provides an additional layer of security by combining encryption with steganographic techniques, ensuring secure communication without altering the perceptual quality of the cover image.

## Features
- **Image Steganography**: Hide text messages within image pixels without noticeable distortion.
- **Encryption & Decryption**: Ensures secure transmission by encoding messages with a passcode.
- **Lossless Data Embedding**: Maintains image quality while storing hidden messages.
- **Cross-Platform Compatibility**: Runs on any system supporting Java and OpenCV.
- **User-Friendly Interface**: Command-line interaction for easy encryption and decryption.

## Technologies Used
- **Python** - Simplicity.
- **OpenCV** – Image processing library.
- **BufferedImage API** – For image manipulation in Java.
- **GitHub** – Version control and collaboration.

## Installation
To set up and run this project locally, follow these steps:

1. Prepare the Environment
Install Python: Make sure you have Python installed on your system. You can download it from python.org.

Install Required Libraries: Install the OpenCV library, which is used for image processing. You can do this by running the following command in your Command Prompt or terminal:

bash
pip install opencv-python
2. Save the Script
Create a Python Script: Open a text editor or an Integrated Development Environment (IDE) like VSCode, PyCharm, or even Notepad.

Copy the Script: Copy the entire script you provided into the editor and save it with a .py extension. For example, save it as steganography.py.

3. Prepare the Image
Image File: Place the image file you want to use for hiding the message (e.g., steno.jpg) in the same directory as your script.

4. Run the Script
Open Command Prompt: Open the Command Prompt and navigate to the directory where your script and image are located.

Execute the Script: Run the script by typing the following command and pressing Enter:

bash
python steganography.py
5. Follow the Prompts
Input Secret Message and Passcode: When prompted, enter the secret message you want to hide and a passcode for encryption.

Check the Encrypted Image: The script will save and open the encrypted image (encryptedImage.jpg).

6. Decrypt the Message
Run the Script Again: To decrypt the message, run the script again.

Input the Passcode for Decryption: When prompted for the decryption passcode, enter the same passcode you used during encryption.

Retrieve the Hidden Message: If the passcode is correct, the hidden message will be printed.

Example Commands
bash
pip install opencv-python
cd 


## Usage
1. **Encrypt a Message:**
   - The program takes an image (`steng.jpg`) and hides the entered message within its pixel data.
   - The Python code for Image Encyption generates an encrypted image (`encryptedsteng.jpg`) containing the hidden message.
2. **Decrypt a Message:**
   - The program reads `encryptedsteng.jpg`, extracts the hidden message, and verifies the passcode.
   - If the passcode matches, it displays the decrypted message.

## Example Execution
```
Enter secret message: Hello, this is a secret!
Enter a passcode: mypass123
Encryption Completed. Encrypted image saved as encryptedImage.png
```

```
Enter passcode for Decryption: mypass123
Decrypted message: Hello, this is a secret!
```

## Future Enhancements
- **Graphical User Interface (GUI)** for easier interaction.
- **Support for Multiple File Formats** (JPEG, BMP, etc.).
- **AES/RSA Encryption** for enhanced security before embedding data.
- **Video Steganography** to hide messages in video frames.

## Contributors
- **Khaja Azharuddin
- **Channabasava Yadav & Vignesh M (Edunet)** – Mentors

## Acknowledgment
Special thanks to **Channabasava Yadav and Vignesh M from Edunet** for their guidance and mentorship in completing this project.

## Contact
For any queries or suggestions, contact:
- **GitHub**:
- **Email**: khajaazharuddin312@gmail.com
