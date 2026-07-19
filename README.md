# ValueStack privacy policy site

One-page static site for the App Store privacy policy URL. `index.html` is
fully self-contained (no assets, no scripts) and adapts to light/dark mode.

## Publish on GitHub Pages

1. Create a new **public** repo on github.com (e.g. `valuestack-privacy`).
2. From this folder:

   ```bash
   git init
   git add index.html README.md
   git commit -m "ValueStack privacy policy"
   git branch -M main
   git remote add origin https://github.com/<your-username>/valuestack-privacy.git
   git push -u origin main
   ```

3. On GitHub: repo **Settings → Pages → Branch: main / (root) → Save**.
4. After a minute the page is live at:
   `https://<your-username>.github.io/valuestack-privacy/`

That URL is what goes in App Store Connect → App Privacy → Privacy Policy URL.
Keep the repo up — Apple occasionally re-checks that the URL resolves.
