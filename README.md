# TeamLite — Simple Team Availability Tracker

Beginner-friendly Flask project using SQLite. **No MySQL setup is required.**

## Features
- Dashboard counts: Total, Available, Busy, Away
- Add and delete team members
- Change member status
- Search by name or role and filter by status
- Saves records locally in `team.db`, created automatically

## Run on Windows
1. Open Command Prompt in this folder.
2. Run:
   ```bat
   python -m venv venv
   venv\Scripts\activate
   python -m pip install -r requirements.txt
   python app.py
   ```
3. Open http://127.0.0.1:5000

## GitHub
Upload source files. Do not upload `venv/` or `team.db`.
