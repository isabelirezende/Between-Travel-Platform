# 🌍 Between

**Between** is a travel connection platform focused on what happens *between destinations*: where strangers meet, plans shift, and real stories begin.

This project was built to demonstrate how no-code tools can be combined with automation to create a real, scalable product.

## 🔗 Live Demo
👉 https://beetwentravel.lovable.app

---

## ✨ Key Features

- Traveler profile creation
- Automated onboarding email
- Data persistence via Google Sheets
- Event-driven automation using n8n Webhooks
- UX-first landing page built with Lovable

---

## 🧩 Tech Stack

- **Lovable** : Frontend & landing page
- **n8n** : Workflow automation
- **Google Sheets** : Lightweight database
- **Email Service (SMTP)** : Automated onboarding
- **Webhooks (HTTP POST)** : System integration

---

## 🔁 User Flow

1. User fills the traveler form on the website
2. Lovable sends the form data via POST to n8n Webhook
3. n8n validates and normalizes the payload
4. Data is stored in Google Sheets
5. A personalized welcome email is sent automatically

---

## 🧠 Why "Between"?

Travel isn’t just about destinations.  
It’s about the moments **between flights and arrivals**, **between strangers and friends**, **between plans and spontaneity**.

That’s where real connections happen.

---

## 🧪 Testing Strategy

- Webhook tested independently with sample payloads
- End-to-end testing performed from UI to email delivery
- Execution logs validated via n8n dashboard

---

## 📸 Screenshots

See `/docs/screenshots` for UI and workflow examples.

---

## 🚀 Future Improvements

- Authentication & user dashboard
- Traveler matching logic
- Location-based recommendations
- Database migration to PostgreSQL or Firebase

---

## 👤 Author

Built by **Isabeli Rezende**  
Information Systems student 
