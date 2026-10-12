# PUSH Strength

Strength, swim and basketball log. Swipe right when you did a session, swipe left to skip it, and the plan adjusts.

## Put it online with GitHub Pages

1. **Unzip** `push-strength.zip`. On a Mac or PC, double-click it. On iPhone, tap it in the Files app.
2. On **github.com**, create a new repository (for example `push-strength`). Set it to **Public**, since free GitHub Pages needs that.
3. In the new repository, click **uploading an existing file**, drag in all the files from the unzipped folder, then click **Commit changes**.
   On iPhone, switch Safari to the desktop site first (the **aA** button, then **Request Desktop Website**) so the upload option shows.
4. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, pick **main** and **/ (root)**, then **Save**.
5. Wait a minute or two. Your app will be at `https://YOUR-USERNAME.github.io/push-strength/`.

## Install it on your iPhone

1. Open that link in **Safari**.
2. Tap **Share**, then **Add to Home Screen**, then **Add**.
3. Open **PUSH Strength** from the home screen and log from there. The home-screen app keeps its own data, separate from Safari.

It works offline after the first open.

## Using it

- **Weights**: the card shows your next session with weights, warm-up sets and plates per side. Swipe right and fill in what you did (tap a set to take a rep off, pick Easy, Clean or Grind). Swipe left to skip and the session moves to the next day.
- **Swim**: swipe right after a swim and enter distance and time. Change your goal under **Goal**.
- **Basketball**: swipe right to check off the game. Tap any day in the calendar to add or remove one.
- **Settings** (gear icon): change lift, swim and game days, copy a backup, or restore one.

## Your data

Everything you log stays on your phone. Nothing is sent anywhere. Copy a backup from Settings now and then and keep it in Notes.

## Updating

To update the app later, upload the new `index.html` to the same repository (it replaces the old one), wait a minute, then open the app once while online.

## Files

| File | What it is |
|---|---|
| `index.html` | The app |
| `manifest.webmanifest` | Name and icons for the home screen |
| `sw.js` | Offline support |
| `apple-touch-icon.png`, `icon-*.png` | App icons |
