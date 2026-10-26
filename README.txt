MY SOCIAL HUB — Android setup

WHAT'S INCLUDED
- index.html: the app interface
- manifest.webmanifest: installable web app settings
- sw.js: basic offline caching
- icon-192.png and icon-512.png: app icons

IMPORTANT
For the full installable app experience, these files need to be hosted on an HTTPS website. Opening index.html directly from a phone's Downloads folder may show the page, but installation and offline features usually won't work.

EASIEST FREE ROUTE (GitHub Pages)
1. On your Android phone, open github.com in Chrome and sign in/create an account.
2. Create a new public repository named my-social-hub.
3. Upload all five files from this ZIP to the repository root.
4. In the repository, open Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch; select main and /(root), then Save.
6. Wait for the published Pages URL shown on that screen (usually https://YOUR-USERNAME.github.io/my-social-hub/).
7. Open that URL in Chrome on Android. Tap ⋮ > Add to Home screen or Install app, then confirm.
8. Open My Social Hub from the new home-screen icon.

CUSTOMIZE YOUR LINKS
1. Open the installed hub and tap Edit links.
2. Paste your own profile URL (e.g. your Facebook profile URL) and tap Save link.
3. Links are saved locally in that browser on that device. They are not uploaded to the website.
4. Repeat for each service. The current simple version edits one service at a time; the Edit links button opens Facebook first. To edit other services, a follow-up version can add a selector for all 8 links.

SECURITY
- Never enter your social media passwords into this hub.
- It only stores profile URLs locally; it does not collect passwords or log into social accounts.
- Each social shortcut opens the service's website; Android may offer to open its app.
