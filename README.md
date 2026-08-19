# Gym Tracker PWA

An installable, offline-first workout tracker for GitHub Pages. Workout data stays in the browser on the device that records it.

## Publish it with GitHub Pages

1. Create a GitHub repository (for example, `gym-tracker`).
2. Upload every file and folder in this project, preserving the `icons` folder.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, then choose `main` and `/(root)`, and save.
5. Open the site address GitHub provides. On a phone, use the browser menu to **Install app** / **Add to Home Screen**.

## Notes

- The first visit must be online so the offline app files can be stored. After that, it works without a connection.
- Rest notifications require permission when you first start a timer. Browser notifications are not guaranteed on every iPhone/browser, but the in-app timer always remains visible.
- Data is intentionally local to the browser. Use **Export my data** periodically as a backup.
- To change the starter routine, edit the `DEFAULT_PLAN` section near the top of `app.js`.
