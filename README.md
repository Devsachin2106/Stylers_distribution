# 📱 iPad & Stylus Distribution System

A web-based iPad and stylus distribution management system for digital exams.

## Features

- **Issue Devices** — Live search students by name/reg no, assign iPad & Stylus
- **Return Devices** — Find active issues, process returns with condition tracking
- **Dashboard** — Stats, department breakdown, recent activity
- **Records** — Full transaction history with filters
- **Students** — Add individual students or bulk import via CSV (combined module)
- **Reports** — Export to Excel/CSV in 6 formats

## Tech Stack

- **Backend**: Python Flask + SQLite
- **Frontend**: Vanilla JS, Inter font — heycampus/Greatify inspired UI
- **Deployment**: Railway / any PaaS

## Run Locally

```bash
pip install -r requirements.txt
python app.py
# Open http://127.0.0.1:5000
```

## Deploy to Railway

1. Fork this repo
2. Go to [railway.app](https://railway.app) → New Project → Deploy from GitHub
3. Select this repo → Deploy

The SQLite database is created automatically on first run.
