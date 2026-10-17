SKILLSPACE frontend update

Replace the existing SKILLSPACE/index.html in your GitHub repository with this index.html, then commit and wait for Vercel deployment.

Changes:
- View Details now opens a dedicated task page with instructions, requirements, budget, deadline, and file submission form.
- Includes a clear $5 test writing task.
- Login includes email and password fields.
- Signup includes password so demo login can check both email and password.
- Demo submissions save submission metadata in browser localStorage only. The actual file is NOT uploaded to a server. This is not production authentication; passwords are stored in browser localStorage and should never be real passwords.
