SKILLSPACE frontend repair package

Included:
- Login and signup screens with email and password fields.
- Task details page with task instructions, requirements, budget and deadline.
- Test task listings and task submission form.
- Matching root and SKILLSPACE-folder copies so either Vercel Root Directory works.
- Simplified Vercel configuration without the legacy `builds` property.

Deploy:
1. In GitHub, open the repository.
2. Replace the repository files with the matching files in this package, or at minimum update SKILLSPACE/index.html and SKILLSPACE/vercel.json if Vercel's Root Directory is `SKILLSPACE`.
3. Commit the changes and wait for Vercel to deploy.
4. Open the deployed site and hard-refresh it.

Important limitations:
This is a frontend demonstration, not a production-ready platform. Demo user data and submission metadata are stored in browser localStorage. Passwords are not securely stored, and selected files are not uploaded to a server. Do not use real passwords or sensitive information. Real authentication, database storage, and file uploads require a backend and secure storage service. Earnings and withdrawals are previews only; no money is moved.
