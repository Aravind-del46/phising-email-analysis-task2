# Task 2: Phishing Email Analysis

## Objective:
Analyze a suspicious email to identify common phishing indicators.

---

## Sample Email Summary:

- **From:** GitHub <GitHub@bigdogdomains.co>  
- **Subject:** Please verify your email address  
- **Body:** Requests email verification for user `ethan@hooksecurity.co`  
- **Link/Button:** “Verify email address” button with unknown redirect  
- **Time:** 11:39 AM

---

## Phishing Indicators Found:

1. **Suspicious Sender Domain** – `bigdogdomains.co` is not a legitimate GitHub domain.
2. **Mismatch Between Brand and Sender** – GitHub brand is used, but email is sent from an unrelated domain.
3. **Urgent Call to Action** – Asking the user to verify their email immediately.
4. **Different Target Address** – Mentions `ethan@hooksecurity.co`, not the actual recipient’s address.
5. **Unverifiable Button Link** – "Verify email" button might redirect to a malicious or phishing site.
6. **Social Engineering Technique** – Exploits the trust in GitHub branding to lure the user.
7. **No Personalization** – Generic greeting like "Demo" or placeholder name used.

---

## Tools Used:

- MXToolbox Header Analyzer  
- Email client header inspection  
- Google Safe Browsing  
- WHOIS Lookup for domain info

---

## Conclusion:

This email is a likely phishing attempt. It uses GitHub branding to trick the user into verifying an email that does not belong to them. The sender’s domain is unrelated to GitHub, which is a major red flag. Users should avoid clicking the button and report the email as phishing.

---
