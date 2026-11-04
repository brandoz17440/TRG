# TRG Selection Program (web app)

The full TRG selection program as a single-page web app: 10-day roster strip, every day sheet, logs, progress charts and the course/test planner. It works offline after the first visit. Each person's log stays in their own browser on their own device.

## Put it on GitHub Pages

1. On GitHub, create a new repository, for example `trg-program`. GitHub Free hosts Pages sites from public repositories only. Pro and Team plans can host from private repositories, but the site itself is still public on the internet.
2. Click **Add file**, then **Upload files**. Drag in everything in this folder: `index.html`, `manifest.webmanifest`, `sw.js`, `README.md`, `.nojekyll` and the `icons` folder. Commit to `main`. (`.nojekyll` is a hidden file; skip it if your computer hides it.)
3. Open **Settings**, then **Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, pick `main` and `/ (root)`, then click **Save**.
4. Allow up to 10 minutes. The Pages settings then show your site address: `https://<your-username>.github.io/<repository>/`.

## Install it on a phone

- **iPhone:** open the address in Safari, tap **Share**, then **Add to Home Screen**. Open it from the Home Screen icon from then on. The Home Screen app and a Safari tab can keep separate logs, so stick to one.
- **Android:** open the address in Chrome, open the menu, then **Install app** or **Add to Home screen**.

## Your log

- Your log lives in your browser on your device. Other people using the same site never see it, and nothing syncs between devices.
- **Back it up:** Setup, Backup, **Export backup**. On iPhone, save the file to Files. To restore it or move to a new phone, use **Import backup** on the new device.
- Safari deletes saved data for websites not used for 7 days. Home Screen web apps keep their own count of days of use, and WebKit says it does not expect their data to be deleted. Export a backup at the end of each cycle anyway.
- **Coming from the Claude app version?** Open TRG Selection Program in Claude, go to Setup, Export backup, then Import backup here.

## Sharing it

Send the site address. Each person sets their own start date, course and fitness test dates, age, 1RMs and kit in Setup.

## Updating

Upload the new `index.html` and `sw.js` over the old ones. The app checks the network first, so the next open shows the new version. Logs stay where they are.
