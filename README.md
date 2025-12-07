
# Multi-Prime Diffie-Hellman (MPDH) Key Exchange
![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Cryptography](https://img.shields.io/badge/Cryptography-Diffie--Hellman-blue?style=for-the-badge&logo=gnuprivacyguard&logoColor=white)
![Multi-Prime](https://img.shields.io/badge/Protocol-Multi--Prime-green?style=for-the-badge)
![AES](https://img.shields.io/badge/Encryption-AES--256-orange?style=for-the-badge&logo=apache)
[![Colab](https://img.shields.io/badge/Open%20in-Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)](https://github.com/Lyynn777/multi-prime-dh/blob/main/multi_prime_dh.ipynb)
![Math](https://img.shields.io/badge/Number%20Theory-Primes-purple?style=for-the-badge)
![License](https://img.shields.io/badge/License-Open%20Source-brightgreen?style=for-the-badge)

---

## **Project Overview**
This project demonstrates a **Multi-Prime Diffie-Hellman key exchange protocol**, where multiple primes are used instead of a single prime, allowing faster computation and secure key generation. The final shared key can be used for **symmetric encryption**, such as AES.

---

## **Features**
- Generate cryptographically secure primes.
- Compute private and public keys for Alice and Bob.
- Compute shared secret keys using multiple primes.
- Compare performance: **Multi-Prime vs Single-Prime DH**.
- Simulate network key exchange.
- Encrypt and decrypt messages using AES.
- Visual flowchart of the protocol.
- Interactive demo in Colab for experimenting with different number of primes and messages.

---

## **Getting Started**

### **Prerequisites**
- Python 3.x
- Libraries: `sympy`, `secrets`, `hashlib`, `matplotlib`, `pycryptodome`, `graphviz`, `ipywidgets`
- (All dependencies are installed in the notebook via `!pip install`)

### **Run the Notebook**
1. Open the notebook in **Google Colab** using the badge above.
2. Run each cell step by step.
3. Explore:
   - Prime generation
   - Key generation for Alice & Bob
   - Shared key computation
   - AES message encryption/decryption
   - Performance comparison
   - Interactive demo (TBA)

---


## **Interactive Demo**
- Use the slider to select **number of primes** (2–15).
- Enter a **message** to encrypt.
- The notebook will display:
  - Final shared key
  - Encrypted message (hex)
  - Decrypted message
  - Whether keys match

---

## **Performance Comparison**
- Benchmarks execution time for **multi-prime** vs **single-prime** DH.
- Visualized as a **bar chart** for easier analysis.

---

## **License**
This project is **open-source**. Feel free to use, modify, and share for educational purposes.

