**QR Code Generator**
This Node.js application allows users to generate a QR code image from a given URL and save the URL into a text file.

**Features**
Uses the inquirer package to prompt the user for a URL input.
Converts the URL into a QR code image using the qr-image package.
Saves the URL into a URL.txt file using the native fs module.

**Prerequisites**
Ensure you have Node.js installed on your system. You can check by running:
node -v

**Installation**
cd <project-directory>

Install the required dependencies:
npm install inquirer qr-image fs

**Usage**

Run the script using:
node index.js

Enter the URL when prompted.
The application will generate a QR code image (qr_image.png) and save the entered URL into URL.txt.

Check the project folder for the generated QR code image and text file.

**Dependencies**
inquirer - To prompt user input.
qr-image - To generate QR code images.
fs - Native Node.js module for file system operations.
