# QR-Code-Generator-
URL to QR Code Generator
This project is a Node.js application that allows users to input a URL through the command line and generates a QR code for that URL.
Using the inquirer package, the application prompts the user to type in a web address. 
The entered URL is then converted into a QR code image using the qr-image package, and the QR code is saved as a PNG file named qr-image.png. 
In addition, the URL is stored in a text file (URL.txt) using Node's native fs module. 
This project showcases how to interact with users via the command line, handle file creation, and generate QR codes, making it a practical tool for quickly turning URLs into QR codes.
