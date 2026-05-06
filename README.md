# FitAI Planner 🌿

An AI-powered diet & workout planner built with React + Vite, powered by Claude AI.

## Screens
- Login
- Profile Setup (3 steps)
- Dashboard with stats & goals
- AI Diet Plan (Claude-generated)
- AI Workout Plan (Claude-generated)
- Progress tracker
- Leaderboard
- Rewards & badges

## Setup

### 1. Install dependencies
```bash
npm install
```

### 2. Add your Anthropic API key
Edit the `.env` file:
```
VITE_ANTHROPIC_API_KEY=your_actual_key_here
```
Get a key from: https://console.anthropic.com/

### 3. Run locally
```bash
npm run dev
```
Open http://localhost:5173 on your computer.

### 4. Open on your phone (same Wi-Fi)
```bash
npm run dev -- --host
```
Then open the IP address shown (e.g. http://192.168.x.x:5173) on your phone browser.

## Deploy to Vercel (free, shareable link)

1. Push this folder to GitHub
2. Go to https://vercel.com → New Project → Import your repo
3. Add environment variable: `VITE_ANTHROPIC_API_KEY = your_key`
4. Deploy — get a public URL you can open on any phone!

## Tech stack
- React 18
- Vite
- Claude API (claude-sonnet-4-20250514)
- No backend needed — runs fully in browser
