StegoCrypt – Secure Steganography Tool
StegoCrypt is a simple but powerful Python tool that hides secret messages or files (like PDFs) inside images. It uses encryption and hashing to make sure your data stays safe and untampered. Everything is done using a Jupyter Notebook, making it easy to understand and use.

 -> What It Does
> Encrypts a message or file before hiding it in an image.

> Uses Fernet encryption (based on AES) to keep data secure.

> Applies SHA-256 hashing to check if the message was changed or tampered with.

> Hides the data in the image using LSB (Least Significant Bit) steganography.

> Lets you extract and decrypt the message or file whenever needed.

 -> How It Works
1.Encryption & Hashing:

 > You write a secret message (or pick a file).

 > It’s encrypted using a secure key and hashed to verify its integrity later.

2.Hiding in Image:

 > The encrypted data is turned into binary and hidden in the pixels of an image.

 > An "end marker" is added to know where the secret data stops.

3.Extraction & Verification:

 > The tool reads back the hidden data from the image.

 > It decrypts it and checks the hash to make sure nothing was changed.

4.File Support:

 > Works not just with messages but also with files like PDFs.

 -> Tools & Libraries Used
> Python

> OpenCV

> Pillow (PIL)

> Cryptography (Fernet)

> Hashlib

> Matplotlib

> NumPy

 -> Why It's Useful

  This project is ideal for learning about:

> Cryptography

> Hashing

> Image processing

> How digital steganography works in the real world

It can be used in real scenarios where secure and hidden communication is needed — especially where sending encrypted messages or files openly is risky.
