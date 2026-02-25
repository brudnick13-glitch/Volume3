# Volume³ — Field Earthwork Calculator

A mobile-first PWA for quick field volume calculations. Runs entirely in Safari on iPhone — no App Store required.

---

## Deploy to iPhone (GitHub Pages)

### Step 1 — Create GitHub repo
1. Go to [github.com](https://github.com) and sign in (or create a free account)
2. Click **New repository**
3. Name it: `volume3`
4. Set to **Public**
5. Click **Create repository**

### Step 2 — Upload files
1. In your new repo, click **Add file → Upload files**
2. Upload all files from this folder:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to repo **Settings → Pages**
2. Under **Source**, select **main** branch, root folder `/`
3. Click **Save**
4. Wait ~60 seconds. Your URL will be:
   `https://YOUR-USERNAME.github.io/volume3/`

### Step 4 — Add to iPhone Home Screen
1. Open Safari on your iPhone
2. Navigate to your GitHub Pages URL
3. Tap the **Share** button (box with arrow)
4. Scroll down and tap **Add to Home Screen**
5. Name it `Volume³` and tap **Add**

The app will now appear on your home screen, launch full screen, and **work offline**.

---

## Features — V1
- Rectangular pile/cut with per-side wall angles
- Flat top option (input top dimensions directly)
- Conical pile with angle of repose reference
- Output in CF, CY, and Tons
- Material density dropdown (25+ materials) with manual override
- Above grade (pile) / Below grade (cut) toggle
- Static 3D isometric preview
- Title and notes fields
- State saved locally — survives closing the app
- Fully offline after first load

---

## Updating the app
To push updates: edit files locally, re-upload to GitHub, and the app will update next time it's opened with a connection.
