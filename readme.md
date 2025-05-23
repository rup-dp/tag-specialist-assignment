# 🎯 GTM Qualification Form Demo

This is a minimal HTML/JavaScript form to demonstrate Google Tag Manager integration and conditional event triggering based on user input. It’s designed as a take-home assignment for a Marketing Automation & Tagging Specialist role.

---

## 🚀 Live Demo

👉 [Host it on Netlify](https://www.netlify.com/) or run locally by opening `index.html` in your browser.

---

## 🛠 Features

- Simple form with fields: **Name**, **Age**, **Occupation**, and **Annual Income**
- Qualification logic:
  - Age ≥ 25
  - Income ≥ $40,000
  - Occupation ≠ “Student”
- Pushes a custom event to `dataLayer` on form submission:
  - `offer_qualified` if the user meets criteria
  - `offer_not_qualified` otherwise

---

## 🧪 GTM Setup

1. **Create a GTM container** at [tagmanager.google.com](https://tagmanager.google.com/)
2. Replace the dummy GTM script in `<head>` of `index.html` with:

```html
<!-- Google Tag Manager -->
<script async src="https://www.googletagmanager.com/gtm.js?id=GTM-XXXXXXX"></script>
