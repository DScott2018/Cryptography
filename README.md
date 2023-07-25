# Cryptography
Python scripts for symmetric encryption of user input data

These scripts use the 'cryptography' library's 'Fernet' class, which is a high level implementation of symmetric encryption. That being said, this is not the best way to encrypt data. It uses symmetric encryption,
which means that both the encryption and decryption script use the same key. It is better practice to use asymmetric encryption, which is where the two processes use different secret keys to encrypt and decrypt. 

To encrypt input data, simply run the encrypt script and put in your own data. Copy the encrypted data and the key. These two strings will be formatted as such: b'COPY_THIS'. Do not copy the 'b' and the apostrophes.

To decrypt the encrypted data, run the decrypt script and put in the data and key that was output from the encrypt script. This will turn the encrypted data back into the original input data.
