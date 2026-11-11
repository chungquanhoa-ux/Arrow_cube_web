# Website for App Store (Support URL + Privacy Policy URL)

Files: `index.html`, `support.html`, `privacy.html`, `style.css`, `app-ads.txt`.

1. Replace `SUPPORT_EMAIL` with your real support email in `support.html` and `privacy.html`
   (find and replace; it appears 6 times, each as a link and as visible text). Check the "Last updated" date in `privacy.html`.
2. Upload the folder to any web hosting (your company site, GitHub Pages, Cloudflare Pages, Netlify).
3. In App Store Connect:
   - Support URL: `https://YOUR-DOMAIN/support.html`
   - Privacy Policy URL: `https://YOUR-DOMAIN/privacy.html`
   - Marketing URL (optional): `https://YOUR-DOMAIN/`
4. Put `app-ads.txt` at the ROOT of the domain you give as Marketing URL: `https://YOUR-DOMAIN/app-ads.txt`.
   Compare the line with the one AdMob shows in Apps, View all apps, app-ads.txt, and use AdMob's if they differ.
