# Keylogger Project

## Description
This project is a basic keylogger that captures and logs keystrokes on a system. The recorded keystrokes are stored in a file named `keylogger.txt` and sent via email to a predefined recipient. This project is intended for educational and cybersecurity awareness purposes only.

## Features
- Captures and saves keystrokes in `keylogger.txt`
- Recognizes special keys like Backspace, Tab, Space, and Enter
- Sends the recorded keystrokes via email
- Runs in the background and stops when the `Esc` key is pressed

## Prerequisites
### Required Modules:
- **smtplib** (Pre-installed in Python)
- **ssl** (Pre-installed in Python)
- **pynput** (Requires installation: `pip install pynput`)

## Installation & Usage
### Clone the Repository
```bash
git clone https://github.com/Sankalp-Reddy/KeyLogger.git
cd keylogger
```
### Install Dependencies
```bash
pip install pynput
```
### Modify the Email Configuration
- Open `keylogger.py`
- Replace `user@domain.com` with your email for both sender and receiver.
- Replace `passcode` with the sender email's password (note: use an app password for security instead of your actual email password).

### Run the Keylogger
```bash
python keylogger.py
```

### Stop the Keylogger
- Press the `Esc` key to exit.

## Security Considerations
- This project should only be used for ethical hacking, penetration testing, or personal security audits.
- Do not use this project for illegal activities, as unauthorized monitoring of keystrokes is a violation of privacy laws.
- Ensure you have permission before running this keylogger on any system.
- If testing on personal accounts, use an app password instead of your actual email password to enhance security.

## Legal Disclaimer
This project is strictly for educational purposes. The author does not take any responsibility for misuse or illegal activities performed using this keylogger.

## License
This project is released under the MIT License.

## Author
**Sankalp Reddy**  
GitHub: [Your Profile](https://github.com/Sankalp-Reddy)

