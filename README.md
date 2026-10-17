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

- **Week**: what you've done this week across lifting, mornings, swim and basketball, day by day, with the weeks before it underneath. Tap a row to go to that tab.
- **Weights**: the card shows your next session with weights, warm-up sets and plates per side.
  - Tap **Start workout** to go set by set. Tap **Done** after each set and a rest timer counts down, then beeps when it's time for the next set (with the ringer on). If you got fewer reps, change the number before tapping Done, or fix it during the rest. After the last set of a lift, pick Easy, Clean or Grind. At the end, tap **Save session**.
  - Or swipe right on the card to log a session after the fact. Swipe left to skip it and the session moves to the next day.
- **Strength level**: on the Weights tab, see how your lifts compare with other lifters at your body weight (from strengthlevel.com), from Beginner to Elite. Tap a lift for the full table and what the next level takes in training.
- **Progress charts**: on the Weights tab, tap a lift to open its chart full screen with a table of every entry. On the other tabs, tap the chart. It stays put until you tap **X**. Tap a point or a row to see that day. Turn your phone sideways to see the table next to the chart.
  - The shaded bands behind the line are the levels, Beginner to Elite. On the lift charts they're shown as the weight for a set of 5 at your body weight, so you can see how close the next level is. The pull-ups chart shows your best set each session, and the swim chart shades the 1 km levels.
- **Mornings**: swipe right after your 5:30 session, check the run distance and time (filled in from last time) and whether you did the punching bag, then tap **Save morning**. Swipe left to skip. Your days off (Friday and Saturday) don't break your streak. Tap a day in the calendar to log or edit it. Tap the grid to see every week and month, and the run chart to see every run.
- **Swim**: swipe right after a swim and enter distance and time. Change your goal under **Goal**. **Level** compares your 1 km time with other swimmers (from swimminglevel.com, adjusted for breaststroke). Under **Technique**, tap any step or tip for the details, common mistakes and a drill. Tap **Make it my next swim's focus** to put that drill on your next swim card.
- **Basketball**: swipe right after a game, then note how it went (energy, cramp, reflux) and what you ate: when, how much, what, and electrolytes, banana and so on. Everything is optional. **Patterns** compares games with and without each habit once you have 3 games with details. Tap a game or a day in the calendar to edit or delete it.
- **Settings** (gear icon): set your body weight and age for the levels, change lift, morning, swim and game days, set rest times, turn the beep on or off, copy a backup, or restore one.

## Your data

Everything you log stays on your phone. Nothing is sent anywhere. Copy a backup from Settings now and then and keep it in Notes.

## Updating

To update the app later, upload all the files from the new zip to the same repository so they replace the old ones. Wait a minute, then open the app once while online. Your log stays on your phone and is not affected.

## Files

| File | What it is |
|---|---|
| `index.html` | The app |
| `manifest.webmanifest` | Name and icons for the home screen |
| `sw.js` | Offline support |
| `apple-touch-icon.png`, `icon-*.png` | App icons |
