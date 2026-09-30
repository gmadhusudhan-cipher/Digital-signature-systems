# Digital Signature Verification System

Source: https://digital-signature-system-o92u.onrender.com/

RSA cryptography-based document authentication and integrity verification

## Project Objective

This system verifies the authenticity and integrity of digital documents using RSA digital signatures and SHA-256 hashing. It detects unauthorized document modifications.

## Generate RSA Keys

Generate a 2048-bit RSA private key and public key.

- Button: Generate Key Pair

## Sign Document

Upload a document and private key to create a digital signature.

- Button: Select Document
- Button: Select Private Key
- Button: Sign Document

## Verify Signature

Upload the document, signature, and public key to verify authenticity.

- Button: Select Document
- Button: Select Signature File
- Button: Select Public Key
- Button: Verify Signature

## Cryptographic Details

- **Asymmetric Algorithm:** RSA
- **Key Size:** 2048 bits
- **Hash Algorithm:** SHA-256
- **Signature Algorithm:** SHA256withRSA

### Verification Workflow

1. Calculate document hash.
2. Verify signature with public key.
3. Compare cryptographic values.
4. Display verification result.

## How to Test Tamper Detection

1. Generate a key pair.
2. Sign a document using the private key.
3. Verify the original document.
4. Modify one character in the document.
5. Verify the modified document using the old signature.

The modified document should produce an INVALID signature result.

---

Digital Signature Verification System | Cryptography PBL Project
