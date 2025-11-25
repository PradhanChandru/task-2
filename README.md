# task-2

1. Overview
This task involves analyzing a suspicious email to identify phishing indicators.
The goal is to understand how attackers trick users using spoofed addresses, fake links, and social engineering.

For this analysis, I used a sample phishing email pretending to be from PayPal.

2. Sample Email Analyzed
<img width="426" height="245" alt="Screenshot 2025-11-25 161315" src="https://github.com/user-attachments/assets/c354b58e-45eb-45ae-b7e9-20f0d387d304" />

3. Phishing Indicators Found
🔴 1. Suspicious Sender Address
The sender address looks similar to PayPal but is actually fake.
“PaypaI” uses a capital I instead of lowercase l — a common spoofing trick.

🔴 2. Fake / Malicious URL
Link in the email:
http://paypal-verify-login-security.com
This is not an official PayPal domain.
Real PayPal uses paypal.com or paypal-inc.com
Hovering over the link reveals a mismatched and dangerous domain.

🔴 3. Urgent / Fear-Based Language
The message claims the account will be locked in 24 hours.
Attackers use fear & urgency to make users click without thinking.

🔴 4. Request for Personal Information
Asking users to “verify identity” is a major red flag.
Legit companies don’t ask for login details by email.

🔴 5. Grammar & Spelling Mistakes
Phrases like “Failure to act will result in account suspension” sound unnatural.
Professional companies avoid bad grammar.

🔴 6. Email Spoofing
Name appears like “PayPal Support,” but the domain is clearly fake.
This is a classic spoofing-based phishing attempt.

🔴 7. Header Analysis (Optional)
Using an online email header analyzer shows:
Server IP does not match legitimate PayPal servers.
“Received from” section contains suspicious mail servers.

4. Final Conclusion
This email shows multiple clear phishing traits.
It attempts to trick users into clicking a fake link and entering sensitive login details.

⚠️ Recommendation:
Do NOT click links from unknown or suspicious senders
Always check the real domain before logging in

Report and delete such emails immediately

