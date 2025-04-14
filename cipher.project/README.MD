# Cipher Analysis Tool

## Project Overview
This tool decrypts various types of classical ciphers (Caesar, Vigenère, and Transposition) from ASCII text files into readable plaintext. Originally developed to solve academic cryptography challenges without prior knowledge of cipher-breaking techniques.

## Features
- **Multiple Cipher Support**: Decrypts Caesar, Vigenère, and Transposition ciphers
- **Automated Analysis**: Detects cipher type and attempts breaking without prior knowledge
- **Frequency Analysis**: Uses statistical patterns in English text for decryption
- **File Processing**: Works with ASCII text files for input and output

## Technologies Used
- Python 3.x
- Statistical analysis libraries
- File I/O handling
- Cryptographic algorithms

## Usage Examples

### Basic Usage
```bash
python cipher_analyzer.py --input encrypted.txt --output decrypted.txt