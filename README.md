# Cryptography Communication System

A secure message communication project that uses three layers of different complex ciphers to protect data in transit.

## Author

**Rajgopal Pandilwar**

## Based On Original Work By


## Encryption Layers

The message is encrypted through three sequential steps:

1. **Reverse Cipher** — The plaintext message is reversed
2. **Vigenère Cipher** — The reversed text is encrypted using the Vigenère cipher with a keyword
3. **Morse Cipher** — The Vigenère output is converted to Morse code

The final output is highly complex and unreadable without knowing all three keys.

## How to Run

Open `CRYPTOGRAPHY_project.ipynb` in Jupyter Notebook or Google Colab and run the cells.

## Tech Stack

- Python 3
- Jupyter Notebook
