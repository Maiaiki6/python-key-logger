# Key Logger

A simple Python keylogger that captures keystrokes and logs them to a file.

## Description

This program uses the `pynput` library to listen for keyboard events. When a key is pressed, it prints the key to the console and appends the character (if available) to a file named `keyfile.txt`.

## Requirements

- Python 3.x
- pynput library

## Installation

1. Install the required library:
   ```
   pip install pynput
   ```

## Usage

1. Run the script:
   ```
   python keylogger.py
   ```

2. The program will start listening for keystrokes. Press keys to log them.

3. The logged characters will be saved to `keyfile.txt` in the same directory.

4. To stop the logger, press Ctrl+C or close the terminal.

## Disclaimer

This tool is for educational purposes only. Keyloggers can be used maliciously and may violate privacy laws. Use responsibly and only on systems you own or have explicit permission to monitor.