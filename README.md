# Week 3: Password Cracking with Dictionary Attacks

A hands-on lab showing how a dictionary attack works against a
password-protected PDF, and what defenders can learn from it.

## Overview
1. Extract the `$pdf$` hash from a protected PDF
2. Hash each word in a wordlist
3. Compare each result against the target hash
4. A match reveals the password

## Tools
- Network Walks Dictionary Attack Lab (Hash Calculator + cracker)
- Wordlists: built-in list (100 passwords) / [custom wordlist]

## Results
- Target: test PDF created for this lab
- Wordlist size: [number]
- Password found: [yes/no], in [time / attempts]

## Defensive takeaways
- Avoid common or dictionary-based passwords
- Use long, unique passphrases
- Store passwords with slow, salted hashes (bcrypt, Argon2)
- Enable MFA wherever possible

## Disclaimer
Performed only on my own test files in a lab environment, for
educational purposes. Do not use these techniques on files or systems
you don't own or have permission to test.# Cybersecurity_Networkwalks_InternshipProject_Week3
