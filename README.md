# rsaEncrypt

RSA Encryption algorithm implemented in C++ 

HOW TO RUN:
-Change the desired string in run.sh file
-"make" in console
-./run.sh in console
-If successful, terminal will output keygen time, encrypt time, string encrypted, and decrypt time
-The keys will be in the directory the program is located (Not the most secure. I'm aware)


init.cc:

    Create a user's public and private keys.
    Save public and private keys to text files

encrypt.cc

    Load user's public key from disk
    Encrypt argv[1] and save the result to message.txt

decrypt.cc

    Load the encrypted message from message.txt
    Decrypt the message
    Print the decrypted message to stdout

utils.cc

    Contains the definitions of constants
    Contains definitions of the structs used to store public and private keys



