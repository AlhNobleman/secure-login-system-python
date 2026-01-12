# Secure Login System

My first real Python project!  
A simple but complete login system with account locking, persistent storage, and admin control.

## Features
- Username + hidden password login
- Account locks after 3 failed attempts
- Failed attempts saved to file (remembers even after restart)
- Successful login clears failed attempts
- Admin mode (username: `admin`, password: `admin123`) to view and unlock locked accounts
- Clean messages, emojis, and thoughtful UX

## How to Run
1. Make sure you have Python installed
2. Run the script
3. Try logging in:
- Normal user example: `Mayowa`(username) / `python`(password)
- Fail 3 times → account locks
- Login as `admin` / `admin123` → unlock users

## What I Learned
- File handling (read/write, persistence)
- `collections.Counter` for counting
- `getpass` for hidden input
- List comprehensions
- Functions, conditionals, and good user experience thinking

Built with lots of debugging in Jupyter Notebook.  
Proud of my first project! 🚀
