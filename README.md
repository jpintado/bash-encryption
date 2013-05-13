bash-encryption
===============

Bash scripts for openssl-encrypted files and folders using aes-256-cbc

## Usage

To encrypt a file or folder:

    ./encrypt FILE
    
To decrypt a encrypted file:

    ./decrypt FILE
    
## Important information

This script uses temporary files to encrypt the compress and encrypt the given file or folder. After the encryption the script tries to remove all the temporary files used, but any unauthorized access to that temporary files is out of the control of this script.

    

