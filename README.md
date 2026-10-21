README — EMAIL FORENSIC COMPARISON
Prepared for Rosemary Ekhaizor | October 20, 2026

RESULT
1. Storage 100% Full: high-confidence phishing/deceptive storage lure.
2. Rainbow ABA / Hipp Health: likely legitimate based on supplied evidence;
   confirm the platform change with a known provider contact before signup.
3. These files do not prove account compromise, malware infection or theft.

FILES
Comparative_Email_Forensic_Report.pdf — formatted detailed report.
Comparative_Email_Forensic_Report.md — editable plain-text Markdown copy.
Evidence_Manifest.json — SHA-256 hashes and sizes of four supplied files
and the PDF decoded from the Rainbow email.
README.txt — this quick guide.

HOW TO READ THE REPORT
Start with section 1 for verdicts and section 3 for the comparison.
Sections 4–7 analyze each email and the embedded Rainbow flyer.
Section 8 explains the reputation screenshots and their limitations.
Section 9 lists defanged investigation indicators.
Section 10 gives practical actions and unanswered questions.
Section 11 records source hashes.

KEY EXPLANATIONS
SPF pass authenticates an envelope domain, not a brand or business claim.
The storage email’s SPF pass does not make it an authentic Google notice.
Rainbow reports SPF/DKIM/DMARC passes; these support authenticity but do
not guarantee harmless links or rule out a compromised sender account.
0% AbuseIPDB confidence does not mean an email is safe. Historical counts,
shared relay reputation and cropped screenshots cannot settle the verdict.
IP geolocation is not the sender’s proven location.
The Rainbow email contains a four-page Welcome to Hipp! PDF. Its three
extracted link annotations point to the same Loom tutorial; it was parsed
locally, not executed or comprehensively malware-scanned.

SAFE NEXT STEPS
Report the storage message as phishing and check storage through the known
service app. Do not follow its upgrade, cleanup or unsubscribe links.
Confirm Rainbow’s migration through an established BCBA/provider contact.
If you entered a password in the storage page, secure that account through
its official app/site and review sessions and multifactor authentication.

SCOPE
Offline analysis of supplied text copies and screenshot PDFs. No live URL
visits, redirect testing, fresh reputation checks, or signature revalidation.
Header authentication results are reported evidence, not independently
verified cryptographic results. No evidence of user interaction was given.
Defanged URLs use hxxp and [.] to avoid accidental clicks. Do not reactivate
them outside an authorized isolated analysis environment.

PRESERVATION
Keep originals unchanged. A future investigator should acquire mailbox
.eml originals and document collection times and custody. The manifest
identifies reviewed bytes, not the authenticity of the underlying messages.
The report includes email identifiers; share it only with intended reviewers.
