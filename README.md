# Enciphering and Deciphering System Exercise

This exercise involves designing an enciphering and deciphering system using polling on the Zybo Z7 board. The system encrypts and decrypts messages using a simple cipher mapping function based on a shift key parameter.

## Overview

- **Objective:** Design a software system that receives an original message for encryption or a ciphertext message for decryption from the SDK console terminal, encrypts or decrypts the input message, and sends the decoded message back to the console.
- **Cipher Method:** Each letter in the message is replaced with another letter according to the defined shift key parameter. For example, with a shift key of 2, "A" becomes "C" during encryption and vice versa during decryption.
- **Example:** Input message: "Vjg swkem dtqyp hqz lworu qxgt vjg ncba fqi." Output message: "The quick brown fox jumps over the lazy dog."

## Getting Started

1. Download the hardware configuration and software project from the folder `cipher_decipher`.
2. Include the provided code files (`main_SDK.c`, `cipher_lookup_table.c`, `cipher_lookup_table.h`) in the SDK project.
3. Load the hardware configuration from Vivado into SDK and open the provided software project.
4. Run the software project to display the menu with two commands: encryption/encipher and decryption/decipher.

## Usage

- Select the command (1 for encryption, 2 for decryption) by typing the corresponding number followed by Enter.
- Follow the prompts to enter the original message for encryption or the ciphertext message for decryption.
- The system will encrypt or decrypt the message and display the decoded result on the SDK console.

## Requirements

- Zybo Z7 development board
- Vivado Design Suite
- SDK (Software Development Kit)

## License

This exercise is provided under an open-source license. See the LICENSE file for details.

