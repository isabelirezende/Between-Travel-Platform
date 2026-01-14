# n8n Workflow – Traveler Onboarding

This workflow handles the onboarding of new travelers who create a profile on the Between platform.

It is triggered by a webhook connected to the Lovable frontend form.

---

## 🔁 Workflow Overview

1. Receive traveler data via HTTP POST (webhook)
2. Normalize and validate the input fields
3. Store the traveler information in Google Sheets
4. Generate a personalized welcome message
5. Send a welcome email automatically

---

## 📥 Webhook Input

**Method:** POST  
**Content-Type:** application/json  

### Expected Payload

```json
{
  "name": "string",
  "nationality": "string",
  "email": "string",
  "destination": "string",
  "travel_dates": "string",
  "interests": "string or array",
  "languages": "string or array"
}
