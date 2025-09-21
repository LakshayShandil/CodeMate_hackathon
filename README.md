# 🚀 Python AI Command Terminal 🚀

> A fully-functioning command terminal built in Python for the CodeMate Hackathon. This project replicates the behavior of a real system terminal while adding powerful, modern features like AI-powered command translation, advanced auto-completion, and command history.

---

## ✨ Features

This terminal meets all mandatory requirements and implements several key optional enhancements to create a powerful and user-friendly experience.

| Mandatory Requirements Met | Optional Enhancements Implemented |
| :------------------------- | :-------------------------------- |
| ✅ Core System Commands    | 🤖 AI-Powered Queries             |
| 🖥️ System Monitoring       | 🧠 Smart Auto-Completion          |
| ⚠️ Robust Error Handling   | 📜 Persistent Command History     |
| 🎨 Responsive CLI          | 🔗 Command Chaining (`&&`)        |
|                            | 🔐 Secure API Key Handling        |

---

## 🛠️ Setup and Installation

Follow these steps to get the terminal running on your local machine.

1.  **Clone the Repository:**
    ```bash
    git clone <your-repo-link>
    cd <your-repo-folder>
    ```

2.  **Install Dependencies:**
    Make sure you have Python 3 installed. Then, run the following command to install the required libraries from the `requirements.txt` file.
    ```bash
    pip install -r requirements.txt
    ```

3.  **Set Up Your API Key:**
    - Create a file named `.env` in the root of the project directory.
    - Add your Gemini API key to this file in the following format:
      ```env
      GEMINI_API_KEY="YOUR_API_KEY_HERE"
      ```

4.  **Run the Terminal:**
    You're all set! Launch the terminal with this command:
    ```bash
    python terminal.py
    ```

---

## 📖 How to Use

-   **Standard Commands:** Type any of the supported commands (e.g., `ls`, `cd ..`, `monitor`).
-   **AI Commands:** Type `ai` followed by your request in plain English (e.g., `ai create a file named report.txt`).
-   **Exit:** Type `exit` to close the terminal.
