# CrackMyPin-SHA-256-
This Python script performs a brute-force attack to crack a hashed numeric PIN by leveraging the SHA-256 hashing algorithm.

# Features
- Accepts any length n-digit PIN (default 6-digit PINs supported).
- Uses SHA-256 to hash PIN attempts and compares them against a target hash.
- Iterates through all possible combinations (from 000...0 to 999...9) to find the original PIN.
- Provides feedback when the PIN is successfully cracked or if the attempt fails.
