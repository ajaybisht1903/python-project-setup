# python-project-setup

🐍 Python Project Setup Guide
A simple, reliable, and repeatable guide to starting any Python project the right way, using PowerShell, virtual environments, and VS Code.

📌 Why This Guide?
If you've ever run into issues like:
ModuleNotFoundError: No module named 'requests'
Environment conflicts
Broken installs ...then this guide will help you start clean, every time.

✅ Prerequisites
1) Install the latest Python from (https://www.python.org/downloads)
2) Enable the checkbox "Add Python to PATH" during the installation.
3) Install Visual Studio Code from code.visualstudio.com.
4) Install the Python extension in VS Code.
5) Open PowerShell as your default terminal.

✅ Enable the checkbox "Add Python to PATH" during install
Install Visual Studio Code
Also install Python extension in VS Code
Open PowerShell as your default terminal

🚀 Steps to Start a Clean Python Project
1. Create a Project Folder
bash>
    mkdir MyAwesomeProject
    cd MyAwesomeProject

2. Create a Virtual Environment (venv)
bash>
    python -m venv venv

    What is venv?
        venv (Virtual Environment) creates an isolated Python environment just for this project.
        Keeps dependencies local.
        Prevents global conflicts.
        Reproducible installs.


3. Activate the Virtual Environment
bash>
    .\venv\Scripts\Activate
You’ll know it's activated when you see (venv) before your path in PowerShell.

4. Install Required Libraries
bash>
    pip install -r requirements.txt  (if you already have)
    pip install requests beautifulsoup4 lxml
Add more packages as needed.

5. Save Dependencies to requirements.txt
bash>
    pip freeze > requirements.txt
This file helps you or others install all dependencies easily:
bash>
    pip install -r requirements.txt

6. Set Interpreter in VS Code
    Press Ctrl+Shift+P → Search: Python: Select Interpreter
    Choose the one from .venv

7. Clean Up Unwanted Files (Optional)
To remove __pycache__, .pyc, or old venvs:

# Delete virtual environment
Remove-Item -Recurse -Force .\venv

# Remove __pycache__ folders
Get-ChildItem -Recurse -Directory -Filter "__pycache__" | Remove-Item -Recurse -Force

# Delete .pyc files
Get-ChildItem -Recurse -Include *.pyc | Remove-Item -Force

💡 Tips and Best Practices
> Always use a venv per project.
> Never install packages globally unless absolutely needed.
> Always commit a clean requirements.txt.

> Exclude venv and __pycache__ in .gitignore.

8. Sample of .gitignore
    venv/
    __pycache__/
    *.pyc
    .DS_Store