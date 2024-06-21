# PRODIGY_CS_03
🔐 Password Strength Checker

This tool checks how strong a password is based on its length, and the use of uppercase and lowercase letters, numbers, and special characters. It was developed using the PyCharm IDE.

## 📖 Overview
The Password Strength Checker evaluates passwords to determine their strength and gives feedback on their security level.

## 🛠️ Features
The tool assesses:
- Length: Classifies as Weak, Moderate, or Strong.
- Character Types: Checks for uppercase, lowercase, numbers, and special characters.
- Overall Strength: Rates the password as Weak, Moderate, or Strong based on all criteria.

## 💻 Requirements
- Python 3.x
- PyCharm IDE

## 🚀 How to Run the Program
1. Clone the repository:
    ```sh
    git clone [repository link]
    cd [repository directory]
    ```

2. Run the program:
    ```sh
    python passwordchecker.py
    ```

## 📂 Code Overview
### File: passwordchecker.py
This file contains the code for the Password Strength Checker.

### Imports
```python
import tkinter as tk
from tkinter import ttk, messagebox
import re
```

### Functions
- `assess_password_strength(password)`: Checks the strength of a password based on length and character types.
- `assess_and_display_password()`: Handles the GUI interaction to assess passwords.
- `clear_results()`: Clears the output fields in the GUI.

### GUI Setup
- `root`: The main application window using Tkinter.
- `entry_password`: Input field for entering the password.
- `button_assess`: Button to start the assessment.
- `button_clear`: Button to clear the results.

### Example Usage
1. Enter a password in the input field.
2. Click "Assess" to check the password strength.
3. The results will show the length, character types, and overall strength.

## 🙏 Thanks and Contributions
Thank you for using this Password Strength Checker. Feedback and contributions are welcome! Feel free to open an issue or submit a pull request with suggestions or improvements.

### Adding this README.md to Your Repository
1. **Create the README.md File:**
   - Open your text editor or IDE.
   - Create a new file named README.md.
   - Copy the content above into the README.md file.
   - Save the file in the root directory of your project.

2. **Upload the README.md File to Your Git Repository:**
   - Go to your repository on GitHub or similar platform.
   - Click on "Add file" > "Upload files".
   - Select your README.md file.
   - Commit the changes with a message about adding the README.
   - Push the commit to your repository.
