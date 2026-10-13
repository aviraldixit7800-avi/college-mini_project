# CareerNest — Standalone Job Portal Frontend

This is a standalone HTML/CSS/Vanilla JavaScript frontend based on the backend domain models (job seeker/recruiter users, jobs, applications, profiles, companies). It is deliberately **not connected to the backend**.

## Run
1. Extract this folder.
2. Open the `job-portal-frontend` folder in VS Code.
3. Install/use the Live Server extension.
4. Right-click `index.html` → **Open with Live Server**.

## Demo accounts
- Job seeker: `seeker@demo.com` / `demo123`
- Recruiter: `recruiter@demo.com` / `demo123`

You can also create a demo account using Register. Data persists in the browser's localStorage under keys beginning with `jp_`. Clear the browser site's local storage to reset the demo data.

## Pages
Home, Browse Jobs, Job Details, Login, Register, Job Seeker Dashboard, Applications, Profile, Recruiter Dashboard, Manage Jobs, Post/Edit Job, Applicants, Company Profile.

## Important demo limitation
Authentication and data are stored in localStorage and are not secure. No backend endpoints or database are called. Resume selection stores the filename only; the file is not uploaded. This is for frontend demonstration, not production use.
