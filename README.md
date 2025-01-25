Technical Explanation of the Python Encryption-Decryption Code

Overview:

This Python script implements a simple encryption and decryption system. It uses basic string manipulation techniques and random character generation to encode and decode messages securely. The program also includes a developer info feature to provide meta information about the script.

Features:

Encryption Process:

Adds random characters before and after the message based on a user-provided key.

Rotates the first character of words with length >= 3 to the end of the word.

Reverses shorter words (length < 3).

Decryption Process:

Strips the random characters based on the key used during encryption.

Restores the original word order by rotating the last character to the start.

Reverses shorter words to their original form.

Developer Info:

Displays a docstring containing the author’s details and project description.

Interactive CLI:

Prompts the user for actions (encrypt, decrypt, developer info, or quit).

Handles invalid inputs gracefully.

