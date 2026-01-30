🎓 Playfair Cipher – Web-Based Encryption System
A web application that demonstrates the Playfair Cipher, a classical symmetric encryption algorithm. Built with Python Flask, HTML, CSS, and JavaScript, this project allows users to encrypt and decrypt text messages interactively and learn the basics of symmetric key cryptography.

🔐 Overview
The Playfair Cipher uses a 5×5 key matrix to encrypt pairs of letters in a message. Users enter a plaintext or ciphertext along with a key, and the system applies the Playfair Cipher logic to encrypt or decrypt the message, showing the results in real time on the web interface.

🧠 Features
✅ Encrypt text messages using a custom key
✅ Decrypt ciphertext back to the original message
✅ Interactive and user-friendly single-page interface
✅ Visual demonstration of symmetric key cryptography
✅ Built using Python Flask for backend and HTML/CSS/JS for frontend

⚙ How It Works

Encryption Steps:

Input a plaintext message and a key.

Generate a 5×5 Playfair matrix from the key.

Divide the text into pairs, adding “X” if needed.

Apply Playfair Cipher rules to each pair to generate ciphertext.

Display the encrypted text in the web interface.

Decryption Steps:

Input the ciphertext and the same key.

Generate the same 5×5 Playfair matrix.

Divide the ciphertext into pairs.

Apply decryption rules to retrieve the original plaintext.

Display the decrypted message.

🖼 Sample Example

Input (Encryption):
Text: HELLO
Key: MONARCHY

Output:
Ciphertext: GYIYBV

Input (Decryption):
Ciphertext: GYIYBV
Key: MONARCHY

Output:
Plaintext: HELLOX

🧩 Technologies Used

Python Flask

HTML

CSS

JavaScript

JSON (for AJAX data exchange)
