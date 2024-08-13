How the Code Works:
Encryption Function (caesar_cipher_encrypt):

Takes a text and a shift value.
Shifts each alphabetical character by the specified amount, wrapping around if necessary.
Non-alphabetical characters are added to the result unchanged.
Decryption Function (caesar_cipher_decrypt):

Calls the encryption function with a negative shift to reverse the encryption process.
Main Function (main):

Asks the user if they want to encrypt or decrypt.
Prompts the user for the message and shift value.
Displays the result and asks if they want to perform another operation.
How to Run:
Copy the code into a Python file, for example, caesar_cipher.py.
Run the script using Python by executing python caesar_cipher.py in your terminal or command prompt.
This program will handle both encryption and decryption based on the user’s choice and will keep running until the user decides to stop.
