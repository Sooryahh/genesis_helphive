# HelpHive

HelpHive is a college volunteering platform built with Python Flask, SQLite, HTML, CSS, and JavaScript.

## Features

- Student and organizer registration/login
- Password hashing
- Browse and search opportunities
- Organizer CRUD for opportunities
- Student registration
- Organizer approval/rejection
- Attendance marking
- Responsive UI
- SQLite database

## Requirements

- Python 3.10+
- VS Code recommended

## Setup

### Windows

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python app.py
```

### Mac/Linux

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python app.py
```

Open http://127.0.0.1:5000

The database is created automatically on first run.

## Demo flow

1. Register an organizer account.
2. Create a volunteering opportunity.
3. Register a separate student account.
4. Open the opportunity and register.
5. Log in as organizer.
6. Open Volunteers.
7. Approve the student and mark attendance.

## Database

- `users`: account details and role
- `opportunities`: volunteering events
- `registrations`: student registrations, status, attendance

## Suggested environment variable

For development:

```bash
set SECRET_KEY=replace-with-a-long-random-secret
```

Mac/Linux:

```bash
export SECRET_KEY="replace-with-a-long-random-secret"
```

## Git commands

```bash
git init
git add .
git commit -m "Initial HelpHive project"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```

Make meaningful commits such as:

- `setup flask project`
- `add database schema`
- `add authentication`
- `add opportunity CRUD`
- `add registration workflow`
- `improve responsive UI`
- `add testing and documentation`

## Limitations and future improvements

- Add CSRF protection before production deployment.
- Use a production WSGI server.
- Add email verification.
- Add admin moderation.
- Add image upload.
- Add pagination.
- Add automated tests.
