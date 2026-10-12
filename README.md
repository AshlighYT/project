# Business Empire Simulator — GitHub Pages Edition

This is the static, browser-local edition of Business Empire Simulator. It uses only HTML, CSS, and JavaScript.

## Publish it for free with GitHub Pages

1. Sign in to GitHub. If you are under 18, follow GitHub's account requirements and ask a parent/guardian for help if needed.
2. Create a new repository. Name it `business-empire-simulator` and choose **Public** (GitHub Pages availability can depend on your plan and repository visibility).
3. On the repository page, choose **Add file → Upload files**.
4. Upload `index.html`, `README.md`, and `.nojekyll` from this folder. Make sure `index.html` is at the repository's top level, not inside another folder.
5. Click **Commit changes**.
6. Open the repository's **Settings** tab.
7. In the left sidebar, select **Pages** (under **Code and automation**).
8. Under **Build and deployment**, choose **Deploy from a branch**.
9. Set the branch to `main` and folder to `/(root)`, then click **Save**.
10. Wait a few minutes, then return to **Settings → Pages**. GitHub will show your published website URL. It normally looks like `https://YOUR-USERNAME.github.io/business-empire-simulator/`.
11. Open that URL and test **Start playing**, buying/selling, businesses, income collection, and **Save now**.

## Game and save behaviour

- Starts with $500 of virtual money.
- Stocks and cryptocurrency are fictional; prices move only inside the game.
- All market activity is imaginary and uses computer-generated traders. There is no player-to-player trading.
- Purchases, business income, XP, levels, and company launch are simulated.
- The save is stored in browser `localStorage` on that device/browser. It does **not** sync across devices, browsers, or private/incognito sessions.
- If you clear browser site data, the save may be deleted. Use **Reset game** only when you intend to erase your current save.
- This is a static single-player game. GitHub Pages does not provide accounts, a database, server-side admin controls, or cross-device cloud saves.

## Updating the game

Edit `index.html` on your computer, then upload the changed file to the repository and commit the change. GitHub Pages republishes it automatically after a short delay. Browser saves usually remain in place as long as the game's local-storage key is unchanged.

## Troubleshooting

- **404 page:** Confirm `index.html` is in the repository root and Pages is set to branch `main`, folder `/(root)`.
- **Pages not enabled:** Check repository **Settings → Pages** and wait a few minutes after saving.
- **Changes not visible:** Refresh the page; if needed, do a hard refresh. Avoid clearing site data if you want to preserve your save.
- **Progress not shared between devices:** This is expected in the local-save edition; cross-device saves require a backend/database.
