# Password Manager 🔐
A Python password manager with a functional GUI that lets you generate secure passwords, save them to a local JSON file, and retrieve them by website name.

# Features
- Generate strong, random passwords

- Save website credentials (website, email/username, password)

- Store data locally in a data.json file

- Search for and retrieve saved credentials

- Auto-copy generated passwords to clipboard

- User-friendly Tkinter interface

# How it works
1. Enter a website name and email/username.

2. Click "Generate Password" to create a secure password.

3. Click "Add" to save the entry.

4. To retrieve a saved password, type the website name and click "Search".

5. All data is stored in a JSON file (data.json) for easy access and persistence.

# Tools and Modules Used
- Python – main programming language

- tkinter – for building the GUI

- random – to generate secure passwords

- json – for saving and reading user data

- pyperclip – to copy passwords to clipboard
(Install it with: pip install pyperclip)

- messagebox – for user alerts (part of tkinter)

# Files
- `main.py`: Main application logic

- `logo.png`: Displayed at the top of the GUI

- `data.json`: Auto-generated file to store credentials

# How to Run
1. Make sure Python is installed on your system

2. Clone or download this repository.

3. Place `logo.png` in the same directory as `main.py`  
   *(Note: The `data.json` file is auto-created in the same directory when you save your first entry — no need to add it manually.)*
   
4. Run the app:

python main.py
or

bash
Copy
Edit
python3 main.py
License
This project is licensed under the MIT License. Feel free to use or modify it for personal use or learning.


