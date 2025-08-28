# Custom Cryptographic Algorithms – Block & Stream Cipher

This repository contains two custom cryptographic systems implemented in Python:

1. **Block Cipher (EduCipher)** – Developed by my teammate:
   - 64-bit SPN structure
   - 10 rounds of substitution (S-box) and permutation (P-box)
   - Cipher Block Chaining (CBC) mode
   - PKCS#7 padding

2. **Enhanced Stream Cipher – Hybrid PRNG** – Developed by me:
   - Combines a 64-bit Linear Congruential Generator (LCG) and a 32-bit Linear Feedback Shift Register (LFSR) with nonlinear mixing
   - Warm-up iterations to reduce seed predictability
   - Keystream XOR encryption/decryption for messages
   - Designed to resist predictability attacks common in basic PRNGs

## Features

- Demonstrates applied cryptography and secure coding techniques
- Highlights differences between block and stream ciphers
- Includes sample message encryption/decryption for both systems
- Evaluates potential weaknesses and suggests improvements

