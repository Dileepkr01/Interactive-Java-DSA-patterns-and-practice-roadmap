# Java DSA Mastery — Shareable Interactive Template

A responsive Java DSA roadmap with 40 patterns, 200 practice problems, Expand All / Collapse All, search, status filters, notes, progress tracking, and export/import.

## Run locally
1. Keep `index.html`, `roadmap.json`, and `config.js` together.
2. Open `index.html` in a modern browser.

## Share it with friends
To count visitors across different devices, publish the folder to a static web host (GitHub Pages is a free option). Opening a local file does not create shared analytics.

### Count visits with Google Analytics 4 (free)
1. Create a Google Analytics account/property at https://analytics.google.com/.
2. Add a Web data stream for the final hosted website URL and copy its Measurement ID (looks like `G-XXXXXXXXXX`).
3. Open `config.js` and set `gaMeasurementId` to that ID.
4. Publish/redeploy the files.
5. View visitors, users, page views, and trends in Google Analytics Reports / Realtime. Custom events also record when a pattern is opened and when a problem is marked solved.

Analytics will remain disabled until you add your own Measurement ID. Do not paste passwords, API secrets, or account credentials into this project. Tell visitors that analytics are in use and follow applicable privacy requirements.

### Optional name/email collection (voluntary)
1. Create a Google Form with fields such as Name and Email. Make the fields optional if you do not need them required, and explain why you are asking.
2. Copy the form's responder URL.
3. Set `visitorFormUrl` in `config.js` to that `https://...` form URL.
4. Redeploy. A voluntary visitor-information link will appear on the page.

**Important:** analytics cannot reliably reveal a visitor's name or email just because they visited. The form is a separate, opt-in action. Do not try to identify people without their knowledge. Store collected details securely and only use them for the stated purpose.

## Free hosting with GitHub Pages
1. Create a GitHub repository for the project.
2. Upload `index.html`, `config.js`, and `roadmap.json` to the repository root.
3. In repository Settings → Pages, select deployment from the `main` branch and root folder.
4. Wait for GitHub Pages to publish, then share the published HTTPS URL.
5. Add the published URL as the Web stream in Google Analytics and update `config.js` with your Measurement ID and optional form URL.

## Progress privacy
Each user's DSA progress is saved in that user's browser storage. Your analytics does not automatically sync their checkboxes or notes to you.


## Creator credit

The website footer credits the project as **Designed & Developed by @Dileep Kumar · B.Tech CSE ’26**.
