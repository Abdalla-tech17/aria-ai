# Aria AI — Your Personal AI Assistant

A full-stack AI chat application powered by Google Gemini.

## Project Structure
```
aria-ai/
├── backend/
│   └── server.js        ← Node.js backend (hides your API key)
├── frontend/
│   └── public/
│       └── index.html   ← Beautiful chat UI
├── .env                 ← Your API key (NEVER share this)
├── .gitignore           ← Keeps .env out of GitHub
└── package.json
```

## Deploy in 5 Minutes (Free)

### Step 1 — Install Node.js
Download from: https://nodejs.org (choose LTS version)

### Step 2 — Install dependencies
Open a terminal/command prompt in this folder and run:
```
npm install
```

### Step 3 — Run locally to test
```
npm start
```
Open http://localhost:3000 in your browser. Aria should work!

### Step 4 — Deploy to Railway (Free hosting)
1. Go to https://railway.app and sign up free with GitHub
2. Click "New Project" → "Deploy from GitHub repo"
3. Upload this folder to a GitHub repo first:
   - Go to github.com → New repository → Upload files
   - Upload everything EXCEPT .env (it's in .gitignore)
4. In Railway, after connecting your repo:
   - Go to "Variables" tab
   - Add: GEMINI_API_KEY = your key here
5. Click Deploy — you get a free public URL!

### Step 5 — Get on Google
1. Go to https://search.google.com/search-console
2. Add your Railway URL
3. Google indexes it within 1–3 days

## Your API Key
Your key is in the `.env` file. NEVER share it or upload it to GitHub.
The `.gitignore` file already protects it.
