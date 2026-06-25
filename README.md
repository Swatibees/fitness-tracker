# 5K Fitness Tracker PWA

Phone-accessible tracker for a 5K running + gym plan.

## Main features

- First screen keeps the main summary clean: weekly progress, run total, latest weight and energy.
- First screen also has date and session type only.
- When you choose Gym, Run or Rest, the app smoothly moves to the session details page.
- Gym days: choose a saved plan, then log exercises with weight, reps, sets and effort.
- Run days: log distance, pace, time, run type and how it felt.
- Daily check-in: body weight, steps, mood, energy level and notes.
- Progress screen: logged days, total runs, best distance, weight change and 5K progress.
- Custom gym plans: add your own plans and exercises.
- Backup/export and import.

## GitHub Pages update steps

1. Unzip this folder.
2. Open your GitHub repository.
3. Upload/replace all files in the repository root:
   - `index.html`
   - `manifest.json`
   - `service-worker.js`
   - `icon-192.png`
   - `icon-512.png`
   - `README.md`
4. Commit the changes.
5. Wait for GitHub Pages to deploy.
6. Open your GitHub Pages link on your phone.

## If your phone still shows the old version

The phone app may be using the old PWA cache. Try these in order:

1. Close the app completely and reopen it.
2. Open the GitHub Pages link in the phone browser and refresh twice.
3. Remove the home-screen app icon and add it again.
4. If needed, clear website data/cache for the GitHub Pages site and reopen the link.

Your data is saved locally in your phone/browser. Use **Data > Export backup** regularly.
