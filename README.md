Python AI Command Terminal
This project is a fully-functioning command terminal built in Python, created for the CodeMate Hackathon. It replicates the behavior of a real system terminal while adding powerful, modern features like AI-powered command translation, advanced auto-completion, and command history.

Features
Mandatory Requirements
Core Commands: Full support for ls, cd, pwd, mkdir, rm, touch, and mv.

System Monitoring: monitor command to display real-time CPU and memory usage.

Robust Error Handling: Provides clear feedback for invalid commands or incorrect arguments.

Responsive CLI: A clean and interactive command-line interface.

Optional Enhancements Implemented
🚀 AI-Powered Queries: Use the ai command to execute tasks using natural language (e.g., ai create a new folder called project_files).

🧠 Smart Auto-Completion:

Press Tab to complete standard commands.

Type ai  and press Tab for contextual, word-by-word suggestions for natural language commands.

Automatically suggests file and folder paths when needed.

📜 Command History: Use the up and down arrow keys to navigate through your command history, which persists between sessions.

🔗 Command Chaining: Execute multiple commands in sequence using && (e.g., pwd && ls).

🔐 Secure API Key Handling: Uses a .env file to securely manage the Gemini API key, keeping it out of the source code.

Setup and Installation
Clone the Repository:

git clone <your-repo-link>
cd <your-repo-folder>

Install Dependencies:
Make sure you have Python 3 installed. Then, run the following command to install the required libraries:

pip install -r requirements.txt

Set Up API Key:

Create a file named .env in the root of the project directory.

Add your Gemini API key to the file in the following format:

GEMINI_API_KEY="YOUR_API_KEY_HERE"

Run the Terminal:

python terminal.py

How to Use
Standard Commands: Type any of the supported commands (e.g., ls, cd ..).

AI Commands: Type ai followed by your request in plain English (e.g., ai tell me the system status).

Exit: Type exit to close the terminal.
