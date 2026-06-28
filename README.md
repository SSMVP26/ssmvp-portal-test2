SSMVP Portal — TEST environment
GitHub Pages hosts the TEST build of the donation portal. TEST uses a separate Google Sheet with dummy data — it is NOT the live system.

What's in here
index.html — the test portal. This is the only file GitHub Pages serves.
SSMVP_AppScript_TEST.gs — backend code, kept here for version control/backup ONLY. It actually runs inside Google Apps Script (bound to the test Sheet), not on GitHub.
Turn on GitHub Pages
Settings → Pages → Source: "Deploy from a branch" → Branch: main / (root) → Save. Site appears at: https://.github.io//

IMPORTANT — test only
Do NOT put the PRODUCTION build in a public repo. Its secret (and your real donor data) would become public. Production stays private, or use Google SSO for public hosting.
