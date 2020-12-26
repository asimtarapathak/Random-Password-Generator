# Password-Generator V2
This is a random password generator build using Python.

<h3>What's the difference in PasswordGenerator and PasswordGenerator V2 ?</h3>
<h4>The difference is that PasswordGenerator only generates the password and able to copy to 
clipboard. Once think if the password is not remembered by the user so in order to save the 
generated password in encrypted file using AES Encryption by generating the key, I have implemented
encrypting and decrypting using cryptography python module. It is secure and without the key no one 
can decrypt the encrypted password</h4>

Modules Used:
<ul>
  <li>PyQt5</li> -> For GUI
  <li>Random</li> -> For randomizing characters
  <li>String</li> -> For generating letters, numbers and punctuation
  <li>pyperclip</li> -> For copying to clipboard
  <li>cryptography</li> -> For generating jey, loading key, encrypting and decryptinh file.
 </ul>
 
 <b>Note:</b> You need to install PyQt5, pyperclip, cryptography before running the script else the program won't work.
<br> To install these modules type this two commands in your terminal:
 <br>-> pip install pyqt5
 <br>-> pip install pyperclip
 <br>-> pip install cryptography
