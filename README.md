KKP TRUCKING SERVICES WEBSITE — PREVIEW / DEPLOY

FILES
- index.html: complete responsive website prototype
- assets/kkp_logo.png: KKP logo asset, if provided

PREVIEW LOCALLY
1. Extract the ZIP file.
2. Keep index.html and the assets folder together.
3. Double-click index.html to open it in Chrome, Edge, or Firefox.
4. Test the plan calculator and demo ledger.

ADMIN ACCESS
- Scroll to "Admin Dashboard"
- Demo code: KKP-DEMO
- Enter a participant name, select a plan, then create/load the local ledger.
- The ledger is stored in the current browser using localStorage. It is not a secure database and is not shared across devices.

IMPORTANT SECURITY LIMITATION
This is a static front-end prototype, not a production-ready secure participant management system. The demo code is visible in the source and is not real authentication. Do not enter real customer, identity, banking, or sensitive financial data. Before production use, add a server-side backend, secure authentication, role-based authorization, a database, backups, HTTPS, validation, audit logging, and a privacy notice/consent flow.

DEPLOY TO STATIC HOSTING (PUBLIC COMPANY WEBSITE ONLY)
Option A — Netlify:
1. Create a Netlify account.
2. Choose Add new site / Deploy manually (wording may vary).
3. Upload the extracted folder containing index.html and assets.
4. Test the generated URL on desktop and mobile.
Option B — GitHub Pages:
1. Create a repository and upload index.html plus the assets folder.
2. In repository Settings, open Pages.
3. Configure deployment from the main branch and root folder.
4. Wait for the public URL and test it.
You can connect a custom domain in the hosting provider's domain settings.

BEFORE PUBLIC LAUNCH
- Replace placeholder address, phone, and email with verified company details.
- Confirm actual services and plan terms.
- Have the plan and marketing language reviewed for legal and regulatory compliance.
- Do not present illustrative figures as guaranteed returns or guaranteed financing.
- A static site cannot securely operate the private admin system. Use a backend before real participant records are collected.
