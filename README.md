# RSA Encryption and Decryption (C)

## Project Overview
A simple C implementation of the RSA public-key cryptography algorithm. The program generates public and private keys, encrypts an integer plaintext, and decrypts the resulting ciphertext.

## Features
- Recursive Greatest Common Divisor (GCD).
- Modular inverse using the Extended Euclidean Algorithm.
- RSA public and private key generation.
- Integer encryption and decryption.
- Displays original, encrypted, and decrypted values.

## Requirements
- GCC compiler
- C programming environment

## Compilation

```bash
gcc rsa_imp.c -o rsa_imp -lm
```

## Run

**Windows:**
```bash
rsa_imp.exe
```

**Linux:**
```bash
./rsa_imp
```

## Usage
1. Enter two prime numbers (`p` and `q`).
2. Select a valid public exponent (`e`) from the displayed options.
3. Enter an integer plaintext between `0` and `n-1`.
4. View the public key, private key, ciphertext, and decrypted plaintext.

## Files
- `rsa_imp.c` – RSA implementation source code.
- `rsa_imp.exe` – Compiled Windows executable.
