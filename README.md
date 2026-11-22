# CSS Command Centre — Current Affairs Syllabus & 2017–2026 Past Papers Edition

This project is designed to run on **GitHub Pages without Netlify**, updated with the **FPSC CSS Current Affairs (100 Marks) Revised Syllabus** and the **2017–2026 Domain-Wise Question Bank (70 Descriptive Questions across 15 Domains)**.

## What Was Updated
- **CSS Syllabus Navigator:** Replaced the generic placeholder syllabus with the complete FPSC Current Affairs (100 Marks) syllabus broken down into Section I (Pakistan's Domestic Affairs — 20 marks), Section II (Pakistan's External Affairs — 40 marks), and Section III (Global Issues — 40 marks), mapped directly to the 15 examination domains.
- **Past Papers & Question Bank (2017–2026):** Integrated all 70 verified descriptive questions (Q. No. 2–8) across 10 examination papers (2017–2026), organized across all 15 subject domains with interactive domain filtering, year filtering, and keyword search.
- **15-Domain Analytical Framework:** Integrated the 15 Current Affairs domains into the Dashboard, Current Affairs Intelligence, Pakistan Affairs, World & Regions, and Revision Library so every domain and past-paper question can be bookmarked, annotated, and sent directly to the Essay & Answer Writing Studio.

## Deploy on GitHub Pages
1. Create a GitHub repository (for example `css-command-centre`).
2. Upload all files and folders from this package to the repository root.
3. Open repository Settings → Pages.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site. Your URL will look like `https://YOUR-USERNAME.github.io/css-command-centre/`.

## Daily scheduled check & Refresh button
- The included GitHub Actions workflow runs daily and records the latest scheduled check timestamp in `data/last-scheduled-check.txt`.
- The browser-side Refresh button retrieves public BBC RSS feeds using the public `rss2json` service and automatically tags incoming articles against the relevant CSS Current Affairs domains.
