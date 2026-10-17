SKILLSPACE frontend demo
========================

Deployment
- Upload index.html, vercel.json, and README.txt into the SKILLSPACE folder in your GitHub repository.
- Vercel should use SKILLSPACE as the Root Directory if that is where these files live.

Task workflow
- Task cards open a full task detail view with instructions, budget, deadline, and a project submission form.
- The submission form validates a selected file (up to 10 MB) and saves submission metadata in browser localStorage for demonstration.
- This is still a frontend-only demo. It does NOT upload the actual file to a server, notify a client, create a server-side job application, or process payment.
- A production version requires a backend, database, secure authentication, and file storage (for example, Supabase or another suitable service).
