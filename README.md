# 📩 AI Job Application Email Generator

An end-to-end no-code tool using Google Forms, Sheets, Zapier, and GPT-3.5 to instantly generate personalized job application emails based on user inputs.

### 💡 Use Case:
- Career coaches
- Resume writers
- College students
- Recruitment firms

### 🔧 Stack:
- Google Forms
- Google Sheets
- Zapier
- OpenAI (GPT-3.5)
- (Optional) Gmail API

### ⚙️ Flow:
1. User fills out form
2. Zapier reads new Sheet row
3. Prompt sent to GPT via API
4. GPT email is returned and sent or stored

### 🔐 Notes:
- Secure key handling (stored in Zapier)
- No sensitive data logged
- GDPR-friendly if opt-in is added

### 🧠 Prompt Used:
Write a {Tone} job application email for the role of {Role} at {Company}.
The applicant's name is {Full Name}.
Keep it under 250 words and professional.


### 🚀 Status:
✅ Built and tested  
✅ Deployed internally  
📦 Ready to offer as a paid micro-service

