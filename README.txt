SKILLSPACE — Referral, Navigation & Visual Polish Update

Contents
- index.html: updated single-page SKILLSPACE frontend demo
- skillspace-logo.svg: full SKILLSPACE logo for the hero/background watermark
- skillspace-mark.svg: compact logo mark for navigation and favicon
- vercel.json: clean URL settings for static deployment
- SKILLSPACE/: duplicate deploy-ready copy for the existing repository layout

Changes in this version
- Added Refer & Earn messaging: members can see referral codes, referral links, referred-client counts, and commissions equal to 25% of each referred client's verified paid membership amount.
- Added optional referral-code field to sign-up and prefill support for referral links using ?ref=CODE.
- Added administrator UI to inspect who referred a client, see each client's own code, assign a custom code, and verify/reject demo membership payment requests.
- Referral commissions are recorded only after an administrator marks a payment as verified in this browser demo.
- Added referral earnings/counts to the member dashboard and profile dashboard summary.
- Added persistent dark/light theme switching in the hamburger menu.
- Added always-visible quick navigation for Home, Categories, Services, Membership, and Dashboard (when logged in), while keeping major links in the menu.
- Added back buttons to pages that do not already have a page-specific back button.
- Made membership plan cards clickable, with keyboard support.
- Non-Premium members can browse Academy course listings; full lessons remain gated behind Premium.
- Randomized task and service listing order so pricing does not automatically appear from lowest to highest.
- Added a custom SVG logo, hero watermark, colorful gradients, floating cards, and Plus Jakarta Sans typography.
- Added referral commission wording to the Terms of Use.

Important prototype limitations
This is still a static frontend demonstration. Browser-local data is not shared between different users, browsers, or devices. A referral code entered by a different user will only validate when the matching referrer record exists in that same browser's local storage. Admin payment verification is a demo control, not confirmation from Safaricom. No live M-Pesa prompt, payment verification, commission payout, or withdrawal transfer is performed. Membership access and admin roles are not secure without a server-side backend. Uploaded work files are not actually sent to remote storage by this frontend alone.

Before production launch, connect secure authentication, a shared database, server-side referral attribution and commission records, role-based admin permissions, actual file storage, and Safaricom Daraja payment initiation/verification. Commission and payout terms should be reviewed before live payments.
