# editorial-crypto
Encryption and Decryption of Editorial Documents

This repository contains two Python scripts that can be installed as Editorial workflows.

Both scripts makes use of the Python AES implementation from Brandon Sterne, which is licensed under the MIT license (see http://brandon.sternefamily.net/files/mit-license.txt).

## EncryptDocument
Encrypts the contents of the current document with a user-defined password, using AES-256 and Base64. 

To decrypt an encrypted document please use the corresponding "Decrypt Document" workflow. 

## DecryptDocument
Decrypts the contents of the current document with a user-defined password, using AES-256 and Base64.

To encrypt a document please use the corresponding "Encrypt Document" workflow.
