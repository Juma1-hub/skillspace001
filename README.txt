SKILLSPACE — Your Online Working Space
=======================================

This repository contains the SKILLSPACE frontend experience.

Files
-----
- index.html: responsive website interface and interactive user flows.
- vercel.json: Vercel static deployment configuration.
- README.txt: project and deployment notes.

Deploy with Vercel
------------------
Place index.html and vercel.json at the repository root, or set Vercel's
Root Directory to the folder containing them. Use Framework Preset: Other.
A plain HTML website does not require a build or install command.

Implementation note
-------------------
This package provides a realistic frontend experience for interface review.
Account creation, task applications, referrals, course progress and withdrawal
requests are currently simulated in the browser. A production backend,
database, secure server-side authentication, admin workflows and approved
payment integrations must be connected before accepting real users or money.

Task budgets shown in USD are test listings for interface review, not live
contracts or guaranteed earnings. Do not use the browser-only account flow
for real passwords or sensitive information.


Update: View details now opens a task details modal, including a dedicated $5 USD test job. Applying to a task is a frontend demo only; no live backend application, payment, or client notification is triggered.
