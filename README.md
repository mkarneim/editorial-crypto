# editorial-crypto
Encryption and Decryption of Editorial Documents

This repository contains two Python scripts that can be installed as [Editorial](http://omz-software.com/editorial/) workflows.

Both scripts make use of the [Python AES implementation](http://brandon.sternefamily.net/wp-content/uploads/2007/06/pyAES.txt) from Brandon Sterne, which is licensed under the [MIT license](http://brandon.sternefamily.net/files/mit-license.txt).
However, all modifications and extensions I made are in the PUBLIC DOMAIN.

## [EncryptDocument](https://github.com/mkarneim/editorial-crypto/blob/master/EncryptDocument.py)
Encrypts the contents of the current document with a user-defined password, using AES-256 and Base64. 

To decrypt an encrypted document please use the corresponding "Decrypt Document" workflow. 

EncryptDocument can be installed from the [Editorial Workflows page](http://www.editorial-workflows.com/workflow/5817532195799040/mZ4VF6bVJGc).

## [DecryptDocument](https://github.com/mkarneim/editorial-crypto/blob/master/DecyptDocument.py)
Decrypts the contents of the current document with a user-defined password, using AES-256 and Base64.

To encrypt a document please use the corresponding "Encrypt Document" workflow.

DecryptDocument can be installed from the [Editorial Workflows page](http://www.editorial-workflows.com/workflow/5774554337116160/tL0TaMd64i4).
