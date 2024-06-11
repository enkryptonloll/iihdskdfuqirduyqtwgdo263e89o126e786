# KaliLinuxWindowsFake Ransomware

## Overview
KaliLinuxWindowsFake is a ransomware application developed in C# using Windows Forms. This ransomware encrypts all files on the victim's computer except for the ransomware itself. The victim needs to input a specific key to decrypt the files. If the correct key is entered, the ransomware decrypts the files and then deletes itself from the victim's computer.

## Features
- Encrypts all files on the victim's computer (except for the ransomware itself)
- Uses AES encryption algorithm for file encryption
- Requires a specific key for decryption
- Deletes the ransomware from the victim's computer after successful decryption

## Usage
1. Run the `KaliLinuxWindowsFake.exe` file.
2. Enter the decryption key and click the "Submit" button.
3. If the key is correct, the ransomware decrypts all the files and then deletes itself from the computer.
4. If the key is incorrect, an error message is displayed, and the decryption process is not initiated.

## Disclaimer
This ransomware is created for educational purposes only. Do not use it on any system without proper authorization. The developer of this ransomware is not responsible for any damage or loss caused by the misuse of this software.
