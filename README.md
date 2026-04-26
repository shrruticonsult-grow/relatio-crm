# Relatio CRM — PWA

AI-powered personal CRM for small business client relationships.

## 🚀 Deploy to Vercel (Free, 5 minutes)

### Step 1 — Upload to GitHub
1. Go to [github.com](https://github.com) → New Repository → name it `relatio-crm`
2. Upload ALL files in this folder (index.html, vercel.json, manifest.json, sw.js)
3. Click **Commit changes**

### Step 2 — Deploy on Vercel
1. Go to [vercel.com](https://vercel.com) → Sign up free with GitHub
2. Click **Add New Project** → Import your `relatio-crm` repo
3. Set **Root Directory** to `public`
4. Click **Deploy** — done in ~30 seconds!
5. You get a free URL like: `https://relatio-crm.vercel.app`

### Step 3 — Install on Android as PWA
1. Open your Vercel URL in **Chrome on Android**
2. Tap the **3-dot menu** → "Add to Home Screen"
3. Tap **Add** — it now appears on your home screen like a real app!

### Step 4 — Add Your API Key
1. Open the app → tap ⚙ Settings
2. Paste your Anthropic API key (get it at console.anthropic.com)
3. Add your name and company name
4. All AI features are now active!

---

## 🔄 Making Future Changes

### Option A — Using the Built-in Change Request Tool
1. Open your app → click **"✦ Request Change"** button on the Dashboard
2. Describe what you want in plain English
3. Claude gives you exact code instructions
4. Open `index.html` in any text editor, apply the changes
5. Push to GitHub → Vercel auto-redeploys in seconds

### Option B — Ask Claude Directly
Come back to this Claude chat and describe the change you want.
Claude can update the code and give you the new files.

### Option C — Edit the Code Yourself
All the app logic is in a single file: `public/index.html`
Search for the section you want to change (SEED_CONTACTS, Dashboard, Pipeline, etc.)

---

## 📁 File Structure

```
relatio-crm/
├── public/
│   ├── index.html      ← The entire app (edit this for changes)
│   ├── manifest.json   ← PWA installability config
│   └── sw.js           ← Service worker (offline support)
└── vercel.json         ← Deployment config
```

---

## 💾 Data & Backup

- All contact data is saved in your **browser's local storage** automatically
- Use **Settings → Export Backup** to download a JSON backup
- Use **Settings → Import** to restore from a backup
- To sync across devices: export on one device, import on another

---

## 🔑 Security Notes

- Your API key is stored **only in your browser** — never on any server
- All AI calls go directly from your browser to Anthropic's API
- Your contact data never leaves your device

---

## 🆘 Troubleshooting

| Problem | Fix |
|---|---|
| AI not working | Check API key in Settings |
| App not installing | Must open in Chrome, not Safari |
| Data lost | Restore from exported backup |
| Changes not showing | Hard refresh (Ctrl+Shift+R) or clear cache |
