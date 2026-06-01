# 🎓 Engineering Admissions Advisor

AI-powered college admissions advisor for top 20 US engineering programs.

---

## 🚀 Deploy to Vercel in 5 minutes

### Step 1 — Install dependencies
```bash
npm install
```

### Step 2 — Add your API key
Edit `.env.local` and replace the placeholder:
```
ANTHROPIC_API_KEY=sk-ant-your-real-key-here
```
Get a key at: https://console.anthropic.com

### Step 3 — Run locally to test
```bash
npm run dev
```
Open http://localhost:3000 — the chat should work!

### Step 4 — Deploy to Vercel
1. Push this folder to a GitHub repo
2. Go to https://vercel.com → New Project → Import your repo
3. In Vercel project settings → **Environment Variables**
   - Add `ANTHROPIC_API_KEY` = your key
4. Click **Deploy** — done! 🎉

Your app will be live at `https://your-project.vercel.app`

---

## 🔒 Security note
- Your API key lives only in `.env.local` and Vercel's environment — never in the browser
- `.env.local` is in `.gitignore` so it won't be committed to GitHub
- The `/api/chat` route proxies all requests server-side

---

## 💰 Cost estimate
- Claude Sonnet: ~$0.003 per conversation turn
- $5 free credits = ~1,600 messages to start
