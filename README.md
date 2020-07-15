# Encrypt
node.js based strong encryption and compression utility

Purified version of:
https://brandonstilson.com/encrypting-files-with-node/

Usage:
```
node aes.js encrypt file.name password
```
Source file won't be overritten, instead a new file with .enc suffix created. Analog for decryption.
```
node aes.js decrypt file.name.enc password
```
