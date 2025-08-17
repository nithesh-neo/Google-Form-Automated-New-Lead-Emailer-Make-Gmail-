# Google-Form-Automated-New-Lead-Emailer-Make-Gmail
# New Lead Emailer Automation 🚀

## 📌 Project Overview
Businesses lose leads when they don’t follow up fast enough.  
This project automates the process: whenever someone submits a Google Form, they instantly receive a welcome email, and the business owner gets notified.

## 🛠️ Tech Stack
- **Make.com** → Scenario orchestration  
- **Google Forms** → Lead capture  
- **Google Apps Script** → Instant webhook trigger  
- **Gmail API (via Make v2 module)** → Email sending  

## ⚡ Workflow
1. **Trigger**: Google Form submission (via Watch Responses or instant webhook).  
2. **Action**: Gmail v2 sends a personalized welcome email to the lead.  
3. **Action**: Gmail v2 sends a notification email to the business owner.  

<img src="<img width="1418" height="857" alt="Screenshot 2025-08-17 at 9 11 22 AM 2" src="https://github.com/user-attachments/assets/e1ef68eb-972a-4033-8df5-31cc7841b7c0" />
" width="600" alt="Make Scenario Screenshothots/make">

## 📬 Example Emails
### Welcome Email (to lead)
Subject: Thanks, [First Name] — we got your inquiry!

Hi [First Name],

Thanks for reaching out to thrivein.ai! We’ve received your message and will reply within 1 business day.

Best,
thrivein.ai
