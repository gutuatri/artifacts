Testing the Resume Creation Hub
Thank you for testing. This is a working beta — real AI calls, real output, genuinely useful. Your job is to break it and tell us what happened.

Before you start
You need a Claude.ai account. Free works. If you hit message limits during testing, note where you were and come back when they reset.
What to have ready:

Your resume (PDF or DOCX preferred, images work too)
Any other career documents — cover letters, bios, LinkedIn PDF exports
A real job posting you want to apply to (copy the full text including requirements)


How to load the tool

Open resume-creation-hub.html in a text editor
Select all and copy (Command+A, Command+C on Mac / Ctrl+A, Ctrl+C on Windows)
Go to claude.ai and start a new conversation
Paste and send
The tool renders in the chat window


Test flow
Work through these in order. Note anything unexpected.
Step 1 — Source docs tab

Upload your resume (drag and drop or click to upload)
Upload any additional documents you have
Confirm each document shows as a chip with its filename
Click Build my profile
Watch the loading screen — it processes each document and shows status

What to check: Does your profile come back with the right roles, education, and skills? Are any companies or positions missing?
Step 2 — Profile tab

Review the Roles section — are all your positions there with the right dates?
Check Education — are your degrees correct and not duplicated?
Look at Skills and Tools — anything obviously wrong or missing?
Try editing a role — click Edit, change a bullet, save it
Try adding a role manually with the + Add role button

What to check: Can you edit everything? Does anything look duplicated or garbled?
Step 3 — Job posting tab

Paste a full job description into the text field
Fill in company name, job title, and location
Click Check gaps + save
Review the gaps that come back
Answer at least 2-3 gaps using the structured interview
Click Save with my answers

What to check: Are the gaps reasonable? Does the structured interview feel clear? Did your answers save?
Step 4 — Generate tab

Select a resume framework (Blend is the default)
Select Classic format
Pick a color
Click Generate
Wait for all four outputs to appear

What to check: Does the resume include your education? Does the cover letter have a proper salutation? Does the honesty check flag anything that's actually in your profile? What grade does the scorecard give?
Step 5 — Download

Click Download .docx on the resume
Open the downloaded file in Word or Google Docs

What to check: Does it open cleanly? Does it look like a real resume?
Step 6 — Feedback tab

Try submitting a piece of feedback
Click Open GitHub issue — does it open GitHub with the feedback pre-filled?


What we most want to know

Did file upload work on the first try?
Did your profile come back complete?
Did the gap interview feel usable or confusing?
Was the generated resume something you'd actually send?
What's the one thing that felt most broken or most confusing?


How to report a bug
Use the Feedback tab inside the tool — it opens a pre-filled GitHub issue at github.com/gutuatri/artifacts/issues.
If the tool isn't working at all, open an issue directly at that link.

Known issues in this beta

File upload works best in Chrome and Firefox. Safari may have issues with drag-and-drop.
Very large documents (over 100,000 characters) will be truncated. Split them into smaller files if needed.
Profile build takes 1-3 minutes with multiple documents. Don't close the window while it's running.
The tool saves your data in the browser. If you clear your browser data or use incognito mode, your profile won't persist between sessions.


Thank you for your time. Every bug report makes this better for the next person who needs it.
