# Task-2
Analyze a Phishing Email Sample.
📌 Overview
This task involves a comprehensive analysis of a phishing email impersonating Amazon. The email was crafted to appear as a legitimate account closure notification from Amazon, aiming to trick the recipient into taking urgent action. Through header inspection and content analysis, several signs of phishing were identified.

🛠️ Email Analysis Process
The suspicious email claimed to be from Amazon with a subject line prompting the user to "Take action to close your Amaazon account." On initial inspection, the email mimicked Amazon's format but contained subtle errors that warranted deeper investigation.

🔍 Tools Used
Google Header Analyzer – Used to inspect and verify authentication results such as SPF, DKIM, and DMARC.
Email Client Link Preview – Hovering over embedded URLs to identify mismatched or suspicious redirections.

⚠️ Key Phishing Indicators Identified
📬 Spoofed Domain Name:
The sender email used @amaazon.in, a visually deceptive variation of the legitimate Amazon domain (amazon.in).

📝 Grammatical & Spelling Errors:
Multiple errors were observed throughout the email body and headers. Notably, "Amazon" was misspelled as "Amaazon", and the content lacked the professional tone typical of corporate communication.

⚠️ Urgent Language Tactic:
The message claimed that the account would be closed within 24 hours if no action was taken. This urgency is a classic social engineering strategy used to induce panic.

| Indicator                 | Description                                                                               |
| ------------------------- | ----------------------------------------------------------------------------------------- |
| 🧑‍💻 Spoofed Domain Name | Sender address used `@amaazon.in`, closely mimicking the legitimate Amazon domain.           |
| 🧠 Urgent Language        | Subject line and content pressured the user to act immediately regarding account closure. |
| 🔗 Misleading Links       | Hyperlinks visually appeared to point to Amazon but redirected elsewhere.                 |
| 🪪 Header Anomalies       | SPF and DKIM checks showed inconsistencies with Amazon’s authentic servers.               |
| 📎 No Attachments         | No file attachment was used, indicating reliance on link-based credential theft.          |
| 📚 Spelling Errors        | Multiple spelling mistakes such as “Amaazon” and inconsistent branding across the email.  |

✅ Conclusion
This email is a clear example of a targeted phishing attempt using spoofed branding, deceptive sender details, and manipulated headers. While the attackers attempted to pass email authentication mechanisms, detailed header analysis revealed the fraud. Spelling inconsistencies, suspicious sending domains, and manipulative urgency reinforce the need for user awareness and robust email security protocols.
