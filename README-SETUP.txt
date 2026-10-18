FOOTBALL LEGACY — FIRST PLAYABLE PROTOTYPE

FILES
- index.html: the entire first prototype in one file. Three.js is loaded from jsDelivr, so an internet connection is needed when opening the game.

ADD THIS FILE TO YOUR EXISTING GITHUB REPOSITORY (ANDROID PHONE)
1. Download index.html from the ChatGPT link.
2. Open Chrome and visit https://github.com/gjinieuglen-cmd/FootballLegacy
3. Sign in to GitHub if asked.
4. Make sure you are on the main branch and the Code tab.
5. Tap Add file, then Upload files. If the mobile page hides Add file, use Chrome menu ⋮ > Desktop site, or open the repository's Code tab on a computer.
6. Choose the downloaded index.html from Downloads. Do not upload the ZIP; upload index.html itself.
7. Scroll down to Commit changes.
8. Commit message: Add first playable 3D football prototype
9. Select Commit directly to the main branch, then tap Commit changes.

PUBLISH AS A WEBSITE WITH GITHUB PAGES
1. In the repository, open Settings.
2. Find Pages (sometimes under the Code and automation section).
3. Under Build and deployment, choose Deploy from a branch.
4. Branch: main. Folder: /(root). Tap Save.
5. Wait for the Pages deployment to finish. Refresh Settings > Pages and open the published URL shown there. It normally looks like https://gjinieuglen-cmd.github.io/FootballLegacy/ . The Settings page is the authoritative place to copy the live URL.
6. Open the published link in Chrome. Use a modern browser and allow internet access so the Three.js library can load.

CONTROLS
- PC: W/A/S/D or arrow keys move; Space shoots; R resets the drill.
- Phone: on-screen arrows move; SHOOT fires when you are close to the ball.
- Walk close to the ball, position yourself facing the goal, then shoot.

TROUBLESHOOTING
- If GitHub says index.html already exists, open the existing file, tap the pencil Edit button and replace its contents with this file's contents; alternatively rename the old file first.
- If the page is blank, open the link while online and refresh. This prototype imports Three.js from jsDelivr, so a blocked CDN or no internet may prevent it loading.
- If you see a 404 for the website, confirm the index.html file is in the repository root and GitHub Pages is configured for main / (root). Deployment can take a few minutes.

NEXT MILESTONES (ADDED ONE STEP AT A TIME)
1. Improve football controls, collisions, and player animations.
2. Add opponents and goalkeeper AI.
3. Add match rules, teams, and match timer.
4. Add career mode, transfers, training, and saves.
5. Later package the web game for Android/iOS/desktop. The first target is the browser game.
