# वेद ज्ञान — Hindu Vedas Explorer (Hindi)

An interactive web app to explore the four Hindu Vedas in Hindi.
Built with Python (Flask) + HTML/CSS/JS. Deploy-ready for Vercel.

## Run locally

```bash
pip install -r requirements.txt
python api/index.py
```

Open http://localhost:5000

## Deploy to Vercel

1. Push this entire repo to GitHub
2. Go to https://vercel.com → New Project → Import your repo
3. Framework: **Other** | Root directory: `.` (leave default)
4. Click Deploy — done! ✅

## Project Structure

```
vedas-hindi/
├── api/
│   └── index.py        ← Flask app (Vercel entry point)
├── requirements.txt    ← flask + gunicorn
├── vercel.json         ← Vercel deployment config
└── README.md
```

## Why api/index.py?

Vercel's Python runtime requires the Flask app to live inside an `api/` folder
and the file must be named `index.py`. The `vercel.json` routes all traffic to it.
