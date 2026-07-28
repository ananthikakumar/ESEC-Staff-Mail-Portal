# ESEC-Staff-Mail-Portal
A web-based staff portal that enables faculty members to upload study materials and automatically send them to students via email using n8n workflow automation, Gmail, and Google Sheets.

🚀 Features
🔐 Staff Login
📄 Upload PDF notes and study materials
📧 Automatic email delivery to students
👥 Sends notes only to students matching the selected Department, Year, and Section
📊 Google Sheets integration for student records
📝 Upload history management
⚡ Automated workflow using n8n
💻 Responsive and user-friendly interface
🛠️ Technologies Used
Frontend
HTML5
CSS3
JavaScript
Automation
n8n
Gmail API
Google Sheets API
Webhooks
⚙️ Workflow
Staff logs into the portal.
Uploads notes along with Department, Year, Section, Subject, and Document Name.
The frontend sends the data to an n8n webhook.
n8n retrieves student email addresses from Google Sheets.
Students are filtered based on Department, Year, and Section.
Gmail automatically sends the uploaded notes to the matching students.
Upload details are stored in Google Sheets for future reference.
