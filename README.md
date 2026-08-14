# 🎉 EventIQ

## AI-Powered Event Automation Platform using n8n

EventIQ is an automation-first event management platform built with **n8n** to automate the complete event lifecycle, including registrations, reminders, attendance tracking, certificate generation, feedback analytics, and organizer communication.

The platform reduces repetitive manual work by connecting forms, notifications, spreadsheets, and event workflows through low-code automation.

---

## 🚀 Project Overview

EventIQ manages the entire event pipeline from registration to post-event feedback.

### Key capabilities

- 📅 Automated event registrations
- 📧 Email confirmations and reminders
- 📲 Telegram notifications for organizers
- 👥 Attendance tracking
- 🏆 Automatic certificate generation
- 📊 Feedback collection and analytics

---

## ✨ Implemented Workflows (5)

### 1️⃣ Registrations Workflow
**File:** `EventIQ - Registrations.json`

- Receives attendee registration data
- Validates submissions
- Stores participant information
- Sends confirmation emails
- Triggers organizer notifications

---

### 2️⃣ Reminders Workflow
**File:** `EventIQ - Reminders.json`

- Sends scheduled reminders before the event
- Supports multiple reminder timings
- Reduces no-show rates
- Automates attendee communication

---

### 3️⃣ Attendance Workflow
**File:** `EventIQ - Attendance.json`

- Records attendee presence
- Updates attendance status
- Maintains participation records
- Supports post-event reporting

---

### 4️⃣ Certificates Workflow
**File:** `EventIQ - Certificates.json`

- Generates personalized certificates
- Inserts attendee details automatically
- Sends certificates via email
- Eliminates manual certificate creation

---

### 5️⃣ Feedback Analytics Workflow
**File:** `EventIQ - Feedback Analytics.json`

- Collects feedback responses
- Processes ratings and comments
- Generates analytics-ready data
- Helps improve future events

---

## 📧 Email Automation

EventIQ automatically sends:

- Registration confirmations
- Event reminders
- Attendance acknowledgements
- Certificate delivery emails
- Post-event feedback requests

---

## 📲 Telegram Notifications

Organizers receive real-time Telegram alerts for:

- New registrations
- Reminder execution
- Attendance updates
- Certificate completion
- Feedback submissions

---

## 🏗️ System Architecture

```text
Registration Form
        │
        ▼
   n8n Webhook
        │
 ┌──────┼──────┐
 ▼      ▼      ▼
Email  Telegram  Storage
        │
        ▼
   Attendance
        │
        ▼
  Certificates
        │
        ▼
Feedback Analytics
```

---

## 🔄 End-to-End Event Flow

1. User submits registration form.
2. Registration workflow validates data.
3. Confirmation email is sent to attendee.
4. Telegram alert is sent to organizer.
5. Attendee data is stored.
6. Reminder workflow sends scheduled notifications.
7. Attendance is recorded during the event.
8. Certificate workflow generates personalized certificates.
9. Certificates are emailed automatically.
10. Feedback workflow collects responses and prepares analytics.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **n8n** | Workflow orchestration |
| **Webhooks** | Event triggers |
| **Email Integration** | Notifications and certificates |
| **Telegram Bot API** | Organizer alerts |
| **Google Sheets / Storage** | Data persistence |
| **AI / LLM APIs** | Optional intelligent processing |

---

## 📂 Repository Structure

```text
EventIQ/
├── EventIQ - Registrations.json
├── EventIQ - Reminders.json
├── EventIQ - Attendance.json
├── EventIQ - Certificates.json
├── EventIQ - Feedback Analytics.json
└── README.md
```

---

## 🎯 Use Cases

- College workshops
- Technical seminars
- Hackathons
- Corporate training sessions
- Community events
- Certification programs

---

## 📌 Project Status

### ✅ Completed
- Registration automation
- Email confirmations
- Telegram notifications
- Reminder automation
- Attendance tracking
- Certificate generation
- Feedback analytics

### 🚧 Future Enhancements
- QR code check-in
- WhatsApp integration
- Multi-event dashboard
- Real-time analytics
- AI event assistant

---

## 🔐 Security

- API keys are excluded from the repository.
- Credentials are managed through n8n credential storage.
- Personal attendee data should be secured in production deployments.

---

## 👩‍💻 Author

**Pawni Jain**  
B.Tech Computer Science Engineering

---
