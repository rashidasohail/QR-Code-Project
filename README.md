<h1>QR Code Generator</h1>

This Node.js application allows users to generate a QR code image from a given URL and save the URL into a text file.

**Features**

1.Uses the inquirer package to prompt the user for a URL input.

2.Converts the URL into a QR code image using the qr-image package.

3.Saves the URL into a URL.txt file using the native fs module.

**Prerequisites**

Ensure you have Node.js installed on your system. You can check by running: node -v

**Installation**

1.cd <project-directory>

2.Install the required dependencies:

3.npm install inquirer qr-image fs

**Usage**

1.Run the script using: node index.js

2.Enter the URL when prompted.

3.The application will generate a QR code image (qr_image.png) and save the entered URL into URL.txt.

4.Check the project folder for the generated QR code image and text file.

**Dependencies**

1.inquirer - To prompt user input.

2.qr-image - To generate QR code images.

3.fs - Native Node.js module for file system operations.
