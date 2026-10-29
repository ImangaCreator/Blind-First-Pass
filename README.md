# Blind First Pass

Identity-blind first-pass resume review for recruiters. A recruiter reviews each resume with names, contact details, links, locations and pronouns hidden, decides Advance or Pass, then locks the stage to reveal names for advanced applicants only.

**This is a demo prototype.** All sample applicants are fictional.

## What works
- Landing page, demo sign-up and sign-in (stored in your browser only)
- Jobs with pay range and requirements
- Resume upload: PDF, Word (.docx) and text
- Pattern-based redaction (no AI)
- Search (redacted text only), status filter, sorting by date, ID or status
- Requirements checklist marked by the recruiter
- Advance or Pass with a reason, lock and reveal, contact export
- Audit log, retention setting, deletion of one or all applicant records

## Demo limits
- **Accounts are not real authentication.** They live in the browser's local storage. Production needs server-side sessions.
- **Live Claude summaries only run when the page is opened inside Claude.** On this site, the 8 sample applicants show summaries prepared in advance, and uploaded resumes show the redacted resume without a summary.
- Data stays in the browser where it was entered.

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.
