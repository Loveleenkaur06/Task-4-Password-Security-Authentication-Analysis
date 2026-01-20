# Task-4-Password-Security-Authentication-Analysis

## Objective
The objective of this task is to understand how passwords are stored securely using hashing, analyze common password attacks, and learn defenses such as strong passwords and Multi-Factor Authentication (MFA).

## Tools Used
* Linux Terminal (LabEx)
* Online Hash Generator (MD5, SHA-256)
* Online Hash Identifier
* GitHub

## Task Description

This task focuses on:

* Understanding hashing vs encryption
* Identifying different hash algorithms
* Generating password hashes
* Learning brute force and dictionary attacks
* Understanding why weak passwords fail
* Studying the importance of MFA
* Recommending strong authentication practices

## Steps Performed

### 1. Hash Generation (Online Tool)

* Generated MD5 and SHA hashes using a test password (`Test@123`)
* Verified hash outputs using an online hash generator

### 2. Hash Generation (Linux Terminal)

Commands used:

```bash
echo -n "Test@123" | md5sum
echo -n "Test@123" | sha256sum
```

This verified how hashes can be generated locally using Linux.

### 3. Tool Availability Check

* Attempted to run `john` and `hashcat`
* Tools were not pre-installed in the lab environment
* Verified tool absence using terminal commands

### 4. Online Hash Analysis

* Used an online hash identifier to analyze generated hashes
* Identified the hash type as MD5


## Screenshots Included

* Online hash generation
* Linux terminal hash creation
* Tool availability check
* Online hash identification

## Key Learnings

* Hashing is a one-way process and cannot be reversed
* Weak passwords are vulnerable to brute force and dictionary attacks
* Fast hash algorithms like MD5 are insecure for passwords
* MFA significantly increases account security
* Strong passwords and secure hashing algorithms are essential

## Tool Availability Note

John the Ripper and Hashcat were not pre-installed in the lab environment.
Tool availability was verified, and online alternatives were used strictly for educational purposes.

## Conclusion

This task provided practical understanding of password security, common attack methods, and modern defenses used to protect user authentication systems.
