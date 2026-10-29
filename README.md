ShareHub – Trusted Resource Sharing

Prototype for the problem statement Unlock Underused Equipment and Spaces.

Serves campus labs and makerspaces: owners list equipment and spaces, users check eligibility, request slots, and every action is recorded.

Live demo: <PASTE YOUR PUBLIC LINK HERE>

Run locally

No install needed. Download the repo and open "index.html" in any browser.

How to test

Use the "Viewing as" dropdown at the top of the page.

1. Meera (Owner) → Listings: publish a new resource, or use the seeded ones.

2. Tom (Community maker) → Discover → 3D Printer Bay → Submit credential for each missing item.

3. Meera → Verifications → Verify.

4. Asha or Tom → Request a slot. Request Ravi's slot (tomorrow 10:00) to see the automatic waitlist.

5. Meera → Requests → Approve, Waitlist or Reject (reason required to reject).

6. Requester → My bookings → "Jump to start" → Check in → Return (choose "Damaged" to auto-create an incident).

7. Meera → Confirm return, then Incidents → Resolve.

8. Open History on any booking, or the Audit log tab.

Use the Reset button to restore the starting data.

Features

Listings with rules and eligibility, search and filters, credential verification, booking requests, conflict detection, waitlist with automatic promotion, fair-use weekly cap and usage-based priority, owner approval/rejection with reasons, check-in/return condition records, damage/delay/incident reports, extensions, cancellations, notifications, role-based views, full audit history.

Tech stack

Single-file HTML, CSS and vanilla JavaScript. No external libraries, templates or APIs. Data is held in memory (resets on reload). All demo data is fictional.

AI disclosure

Built with assistance from Claude (Anthropic) for code generation; reviewed and tested by the team.

Known limitations

No real authentication, no backend or database, no document upload, no real email/SMS notifications.

Team - NEPTUNEX

Name and contribution
Pooja M K| Prototype (Frontend and Logic)| Built the working ShareHub prototype: resource listings, eligibility checks, booking requests, approval and waitlist workflow, check-in and return with condition records, incident reporting, fair-use rules, notifications and audit history. Set up the GitHub repository and hosting.
Pragathi S| Presentation| Prepared the project presentation and demo flow, and organised the project documentation for submission.
Neha K R| Research| Researched the problem of underused institutional equipment and spaces, identified target users and owners, and gathered the evidence used to justify the solution.
