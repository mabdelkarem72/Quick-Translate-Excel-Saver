# 🚀 Quick Translate & Excel Saver

A lightweight Python tool that listens for a global hotkey, translates the current clipboard text, and saves it directly into an Excel file with a desktop notification.

## ✨ Features
- **Instant Translation:** Uses Google Translate API (via `deep_translator`).
- **Silent Background Operation:** Runs in the background without disturbing your workflow.
- **Auto-Excel Logging:** Automatically creates and updates `words.xlsx`.
- **Desktop Notifications:** Stay informed when a word is successfully saved.
- **Customizable Hotkey:** Default is `Ctrl + Shift + K`.

## 🛠️ Built With
- Python 3.x
- `pyperclip` - For clipboard management.
- `keyboard` - For global hotkey listening.
- `openpyxl` - For Excel file manipulation.
- `plyer` - For cross-platform notifications.

## 🚀 How to Use
1. Clone the repo.
2. Install dependencies: `pip install -r requirements.txt`.
3. Run the script: `python translator_tool.py`.
4. Copy any word and press `Ctrl+Shift+K`.
