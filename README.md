# वेद ज्ञान — Hindu Vedas Explorer (Hindi)

An interactive web app to explore the four Hindu Vedas in Hindi.
Built with Python (Flask) + HTML/CSS/JS. Deploy-ready for Vercel.

## Run locally

```bash
pip install -r requirements.txt
python app.py
```

Open http://localhost:5000

## Deploy to Vercel

1. Push this repo to GitHub
2. Go to https://vercel.com → New Project → Import your repo
3. Framework: Other | Root directory: `.`
4. Deploy — done!

## Structure

```
vedas-hindi/
├── app.py              # Flask app
├── requirements.txt    # Python deps
├── vercel.json         # Vercel deployment config
├── templates/
│   └── index.html      # Full app (Hindi UI)
└── README.md
```
