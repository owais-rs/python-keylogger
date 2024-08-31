# python-keylogger

This Python keylogger is a comprehensive tool designed to monitor and log keystrokes, capture system information, clipboard content, audio recordings, and screenshots. It also includes functionality for encrypting captured data and sending it via email.

## Features

- **Keystroke Logging:** Records all keyboard inputs and saves them to a file.
- **System Information Capture:** Gathers details about the system such as the processor, operating system, machine name, IP addresses, etc.
- **Clipboard Monitoring:** Captures and logs the content of the clipboard.
- **Audio Recording:** Records audio using the microphone for a specified duration.
- **Screenshot Capture:** Takes screenshots at intervals.
- **Data Encryption:** Encrypts the collected data using the `cryptography` library before sending it.
- **Email Delivery:** Sends the encrypted logs to a specified email address.

## Prerequisites

- Python 3.x
- Required libraries (can be installed using pip):
  - `pynput`
  - `sounddevice`
  - `scipy`
  - `cryptography`
  - `Pillow`
  - `requests`
  - `smtplib`
  - `win32clipboard` (Windows-specific)

## Setup

1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd <repository-directory>
