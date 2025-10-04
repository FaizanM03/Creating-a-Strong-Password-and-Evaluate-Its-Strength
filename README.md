# Strong Passwords & Attacks — README

This repository contains a short guide to creating and evaluating strong passwords, explains common password attacks, and summarizes how password complexity affects security.

## Contents
- `password_summary.pdf` — concise PDF summary (this repo).
- `README_passwords.md` — this file (human-readable README).
- Examples: a sample strong password and its strength evaluation.

## Sample strong password (DO NOT reuse for real accounts)
`G7!vR9#xTq2&bKz4`  (16 characters — random mix of upper/lower/digits/symbols)

> **Important:** Treat example passwords as educational only. Always generate unique passwords per account and store them in a reputable password manager.

## How strength was evaluated (entropy)
Entropy was calculated using the formula **E = L × log2(R)** where:
- **L** = length of the password (16)
- **R** = size of the character set (we used 94 printable ASCII characters)
- **Entropy ≈ 16 × log2(94) ≈ 104.9 bits**

Higher bits of entropy ≈ exponentially harder to brute-force.

## Quick recommendations
- Use a password manager and enable Multi-Factor Authentication (MFA).
- Prefer long passphrases (>= 16 characters) over short "complex" passwords.
- Avoid reused passwords across sites (prevents credential stuffing attacks).
- Do not rely on composition rules only (NIST suggests allowing long passphrases and not forcing specific character classes).

## Files in this repo
- `password_summary.pdf` — one-page concise summary (same content, printable).
- `README_passwords.md` — this file.
