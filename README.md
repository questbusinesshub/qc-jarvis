# QUEST JARVIS — Vercel Deployment Guide
## Vinayak's Personal AI System

---

## HOW TO DEPLOY (5 steps)

### STEP 1 — Get your Anthropic API Key
1. Go to https://console.anthropic.com
2. Click "API Keys" → "Create Key"
3. Copy the key (starts with sk-ant-...)

### STEP 2 — Upload to GitHub
1. Go to https://github.com → New Repository
2. Name it: quest-jarvis
3. Upload ALL files from this folder:
   - vercel.json
   - package.json
   - api/chat.js
   - public/index.html

### STEP 3 — Deploy to Vercel
1. Go to https://vercel.com → Sign up free
2. Click "Add New Project"
3. Connect your GitHub and select quest-jarvis
4. Click Deploy

### STEP 4 — Add API Key (IMPORTANT)
1. In Vercel: Go to your project → Settings → Environment Variables
2. Click "Add New"
3. Name: ANTHROPIC_API_KEY
4. Value: (paste your key from Step 1)
5. Click Save → then Redeploy

### STEP 5 — Use on Phone
1. Copy your Vercel URL (like: quest-jarvis.vercel.app)
2. Open in Chrome on your phone
3. Tap menu (3 dots) → "Add to Home Screen"
4. JARVIS is now an app on your phone!

---

## VOICE COMMANDS
- Tap 🎙️ button to speak
- Hold SPACEBAR on keyboard to speak
- Press ESC to cancel
- JARVIS speaks back automatically

## FEATURES
- 8 AI Agents: JARVIS Personal, Research, Lead Gen, Sales, Marketing, Automation, Growth, Knowledge
- 6 Modes: Business, Personal, Health, Finance, Creative, Focus
- Life OS: Daily goals for Body, Mind, Wealth, Relationships, Spirit
- Morning Briefing and Evening Review
- Full Indian market knowledge (₹ pricing, WhatsApp outreach, Hinglish scripts)
- Voice input + voice output
- Works on mobile (add to home screen)

## SUPPORT
If you see "API key not set" error → go to Vercel → Settings → Environment Variables → Add ANTHROPIC_API_KEY
