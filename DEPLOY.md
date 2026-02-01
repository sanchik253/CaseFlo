# Deploy BCBA Caseload App

## Easiest Option: Netlify Drop (No account needed initially)

1. Go to https://app.netlify.com/drop
2. Drag and drop this entire `bcba-pwa` folder onto the page
3. You'll get a URL like `random-name-123.netlify.app`
4. Open that URL on your phone
5. **Install as app:**
   - iPhone: Tap Share → "Add to Home Screen"
   - Android: Tap menu (⋮) → "Install app" or "Add to Home Screen"

Your data saves automatically in your browser's localStorage.

---

## Alternative: GitHub Pages (Free, permanent URL)

### First time setup:
1. Create a GitHub account at github.com (if you don't have one)
2. Create a new repository called `bcba-caseload`
3. Upload all files from this folder
4. Go to Settings → Pages → Source: "main" branch → Save
5. Your app will be at: `https://YOUR_USERNAME.github.io/bcba-caseload`

---

## Alternative: Vercel (Free, fast)

1. Go to https://vercel.com
2. Sign up with GitHub
3. Import your repository (or drag/drop folder)
4. Auto-deploys to a `.vercel.app` URL

---

## How Data Persistence Works

- All data saves to your browser's **localStorage**
- Data persists as long as you:
  - Use the same browser
  - Don't clear browser data
  - Access via the same URL

**Backup tip:** Periodically export your monthly reports (PDF) as a backup of your records.

---

## Limitations of This Testing Version

- Data is local to your device/browser only
- No sync between devices
- If you clear browser data, you lose your data
- No push notifications (would require native app)

This is perfect for testing the workflow over a few weeks. If it works well, we can discuss options for a more robust solution (cloud sync, native app, etc.)
