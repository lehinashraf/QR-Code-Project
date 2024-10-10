# QR Code Generator

This Node.js project generates a QR code image from a URL input provided through the terminal. The output is saved as a QR code image file.

## Features
- Takes a URL as input from the terminal.
- Generates a QR code image for the input URL.
- Saves the QR code image as a .png file.

## Prerequisites
Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v12.0.0 or later)
- npm (comes with Node.js)

## Installation
1. Clone this repository: git clone git@github.com:username/qr-code-generator.git and navigate to the project directory using cd qr-code-generator.
2. Install the dependencies by running: npm install.

## Usage
1. Run the script by providing a URL as input from the terminal: node index.js.
2. When prompted, enter the URL you want to generate the QR code for (e.g., https://example.com).
3. The QR code image will be generated and saved as qrcode.png in the project directory.

## Example
```bash
$ node index.js
Enter the URL: https://example.com
QR code generated and saved as qrcode.png
