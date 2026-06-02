# वेद ज्ञान — Hindu Vedas Explorer (Hindi)

## Deploy to Vercel

1. Push all files to GitHub (root level, no subfolders needed)
2. Vercel → New Project → Import repo
3. Framework: **Other** | Root: `.`
4. Deploy ✅

## Run locally

```bash
pip install flask
python index.py
```

Open http://localhost:5000

## File structure (keep it flat at root)

```
/
├── index.py          ← Flask app + full HTML
├── requirements.txt  ← flask only
└── vercel.json       ← Vercel config
```
