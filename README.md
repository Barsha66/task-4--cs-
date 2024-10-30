# Description
This script listens for keyboard input and logs each keystroke into a file called key_log.txt. The script captures both character and special keys. It runs until the "Escape" key is pressed, which stops the logging.

Warning: Ensure you have permission to run this script on any system, as unauthorized use of keyloggers is illegal.

# Features
Logs every key press to a specified log file (key_log.txt).
Supports both character and special keys (e.g., space, enter).
Stops logging when the "Escape" key is pressed.

# Usage
Installation: Install pynput if you haven’t already.
pip install pynput
Run the Script: Save the script in a Python file (e.g., keylogger.py) and run it with:
python keylogger.py
Stop Logging: Press the "Escape" key to stop the logging process.

# Example
Here’s a sample of the output you might see in key_log.txt:
h
e
l
l
o
Key.space
w
o
r
l
d
Key.enter
Each key press is logged on a new line, and special keys are denoted by their Key.<name> representation.

# Contribution
Contributions are welcome! Feel free to open issues or submit pull requests to improve this script or add new features.
