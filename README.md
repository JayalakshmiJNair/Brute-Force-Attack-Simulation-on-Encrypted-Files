# Brute Force Password Cracker for ZIP & PDF

This Python tool attempts to brute-force password-protected ZIP and PDF files using a dictionary attack with the RockYou wordlist or any other provided wordlist. The GUI is built with Tkinter.

## Features
- Supports brute-force attacks on ZIP files.
- Supports brute-force attacks on encrypted PDF files.
- Uses the RockYou wordlist or any other specified wordlist.
- Provides a visual cracking animation.
- User-friendly GUI with file selection and attack initiation.

## Prerequisites
Ensure you have Python installed along with the required dependencies.

### Required Libraries:
Install them using:
```sh
pip install pikepdf
```

## How to Use

### 1. Selecting and Cracking a ZIP or PDF
- Run the script: `python brute_force_cracker.py`
- Click **Select ZIP File** or **Select PDF File** to choose a locked file.
- Click **Start Attack** to begin the brute-force process.
- If the password is found, it will be displayed on the screen and saved in a message box.

## File Structure
```
/Brute-Force-Cracker
│── brute_force_cracker.py  # Main application script
│── README.md               # Project documentation
│── rockyou.txt             # Dictionary wordlist (if available)
```

## Notes
- The wordlist path should be updated if you are using a different dictionary.
- The RockYou wordlist is large; consider using a smaller custom wordlist for faster cracking.
- The application uses threading to prevent GUI freezing during execution.

## License
This project is open-source and available under the MIT License.

