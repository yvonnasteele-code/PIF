Swarna Andhra @2047 — Newsletter 02 (Case Studies)
A single self-contained web page. All fonts, both logos, the district map,
the popups, the quick-feedback buttons and the styling are embedded in
`index.html`, so there is no build step and no dependencies to install.
The only outward links are the buttons: the dashboard case-studies section,
Google Classroom, and the Google feedback form. Each opens in a new tab.
Deploy on Vercel
Option A — from GitHub (recommended)
Create a new GitHub repository and add `index.html` at the repository root.
(This README is optional.)
Go to vercel.com, New Project, and Import that repository.
Framework Preset: Other. Leave Build Command and Output Directory empty.
Deploy. Vercel serves `index.html` at the root URL.
Option B — no GitHub
Drag the folder containing `index.html` onto vercel.com, or run `vercel`
from the folder with the Vercel CLI.
Updating
Replace `index.html` and push; Vercel redeploys automatically.
