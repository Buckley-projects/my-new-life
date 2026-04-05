# ⚡ My New Life Dashboard — PWA Setup

## Files in this folder
- `index.html` — The app
- `manifest.json` — Makes it installable
- `sw.js` — Service worker (offline + notifications)
- `icon-192.png` / `icon-512.png` — App icons
- `icon.svg` — Source icon

---

## How to get it on your iPhone/iPad (GitHub Pages)

### Step 1 — Create a GitHub account
Go to **github.com** and sign up (free).

### Step 2 — Create a new repository
1. Click **+** → **New repository**
2. Name it: `my-new-life` (or anything you want)
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload your files
1. Click **Add file** → **Upload files**
2. Drag ALL files from this folder into the upload area:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to **Settings** (tab at top of repo)
2. Scroll down to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Branch: **main**, Folder: **/ (root)**
5. Click **Save**
6. Wait ~60 seconds, then your URL will be: `https://YOUR-USERNAME.github.io/my-new-life`

### Step 5 — Add to iPhone Home Screen
1. Open Safari on your iPhone (must be Safari, not Chrome)
2. Navigate to your GitHub Pages URL
3. Tap the **Share** button (box with arrow)
4. Scroll down → tap **Add to Home Screen**
5. Name it **My New Life** → tap **Add**

The app icon now lives on your home screen. It opens full-screen with no browser UI.

---

## AI Coach Setup
The Coach tab requires your own Anthropic API key:
1. Go to **console.anthropic.com**
2. Sign in → **API Keys** → **Create Key**
3. Copy the key
4. Open the Coach tab in the app → tap **Set Up API Key**
5. Paste and save

The key is stored only on your device.

---

## Push Notifications
After adding to home screen (Step 5):
1. Open the app from your home screen
2. iOS will ask for notification permission — allow it
3. You'll get contextual reminders based on time of day

**Important**: Notifications only work when launched from home screen, not from Safari directly. This is an iOS restriction.

---

## Your Vision
Go to **Journal** tab → **My Vision Statement** → write your vision → **Save Vision**.

The next morning you open the app (between 4am–2pm), it will show your vision full-screen before anything else.

---

## Updating the App
When you want to update:
1. Make changes to `index.html` locally
2. Go to your GitHub repo
3. Click on `index.html` → the pencil icon (edit) → paste new content → **Commit**
4. Changes go live within ~60 seconds
