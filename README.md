# Bluetooth Connection Web App

## Overview
This web application demonstrates how to establish a Bluetooth connection with a printer device using web Bluetooth API. It allows users to connect to a Bluetooth printer and send print jobs to it.

## Prerequisites
- A web browser that supports the Web Bluetooth API. (Chrome, Edge, Opera)
- A Bluetooth printer that supports the necessary services and characteristics for printing.

## Usage
1. Open the web application in a supported web browser.
2. Click on the "Connect" button to initiate the Bluetooth device discovery process.
3. Select the desired printer device from the list of available devices and pair with it.
4. Once connected, the "Print" button will be enabled.
5. Click on the "Print" button to send a print job to the connected printer.

## Troubleshooting
- **Bluetooth Not Supported**: If the browser does not support Bluetooth, an error message will be displayed, and the application will not function properly.
- **Failed to Connect**: If there is an error while connecting to the printer device, an error message will be displayed, and the connection attempt will be terminated.
- **Failed to Send Print Job**: If there is an error while sending a print job to the printer device, an error message will be displayed, and the print job will not be sent successfully.

## Development
- This web application is built using HTML, CSS, and JavaScript.
- The Web Bluetooth API is used to establish a connection with the printer device.
- The application consists of two main functions:
  - `connect()`: Handles the process of connecting to a Bluetooth device.
  - `print()`: Handles the process of sending a print job to the connected printer.
