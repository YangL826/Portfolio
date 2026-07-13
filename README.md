# Yang Li — Professional Portfolio

Static site for AIML-500 (Indiana Wesleyan University), hosted on GitHub Pages.

## Structure
```
index.html                      Professional Bio + Personal Value Proposition + artifact index
artifacts/interviewchatbot.html Artifact 01 — follows the required 10-section template
assets/style.css                Shared stylesheet
images/                         Screenshots (add shot-01.png, shot-02.png, shot-03.png)
.nojekyll                       Serve files as-is
```

## Deploy in 5 minutes

1. Create a **public** repo on GitHub named `portfolio`.
2. Upload every file here, preserving folders (drag-and-drop into GitHub's web uploader works).
3. Repo → **Settings** → **Pages**.
4. Source: **Deploy from a branch**. Branch: **main**, folder: **/ (root)**. Save.
5. Wait ~1 minute. Your site is live at `https://<your-username>.github.io/portfolio/`

Or via command line:
```bash
git init && git add . && git commit -m "Portfolio: Artifact 01"
git branch -M main
git remote add origin https://github.com/<your-username>/portfolio.git
git push -u origin main
```

## Before submitting

- [ ] Add three screenshots to `/images` (shot-01.png, shot-02.png, shot-03.png)
- [ ] Replace the three TO DO notes (bio contact links, screenshots, references)
- [ ] Open the site in an incognito window — confirm no login wall
- [ ] Confirm the Mizou bot link works while logged out
- [ ] Paste the reflection into the Brightspace text area — NOT into this site
