# Secure-Image-Based-Data-Hiding-Using-Steganography

# Image Steganography Using LSB Technique

A Python-based steganography project that securely hides a secret message within an image using the Least-Significant-Bit (LSB) encoding technique.

## Overview
This project allows users to embed a secret message along with a passcode into an image and later retrieve it using the correct passcode. It consists of two Python scripts with user-friendly graphical interfaces built using Tkinter.

## Features

- **Encryption:**  
  Embeds a secret message and passcode into `mypic.jpg` and saves the modified image as `encrypted.png`.

- **Decryption:**  
  Extracts the hidden message from `encrypted.png` when the correct passcode is provided.

- **User-Friendly GUI:**  
  Simple and intuitive Tkinter-based interfaces for both encryption and decryption.

- **Secure Data Encoding:**  
  Uses a structured header format to store the passcode and message lengths for accurate retrieval.

## Requirements

- Python 3.x  
- OpenCV  
- NumPy  
- Tkinter (included with Python by default)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/image-steganography.git
   cd image-steganography
   ```
2. Install the required libraries:
   ```bash
   pip install opencv-python numpy
   ```
3. Place an image named `mypic.jpg` in the project directory.

## Usage

### Encrypt a Message
1. Run the encryption script:
   ```bash
   python encrypt.py
   ```
2. Enter your secret message and passcode in the GUI.
3. Click "Encrypt" to save the encoded image as `encrypted.png`.

### Decrypt a Message
1. Run the decryption script:
   ```bash
   python decrypt.py
   ```
2. Enter the correct passcode in the GUI.
3. Click "Decrypt" to retrieve the hidden message.

## Notes
- Ensure `mypic.jpg` is of sufficient size to store the secret message.
- The passcode is required to correctly extract the hidden message.
- The encrypted image should be stored in PNG format to preserve data integrity.


---
Developed by Sree Chandan Tangella
