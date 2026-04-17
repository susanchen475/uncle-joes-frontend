# uncle-joes-frontend-
Vue.js frontend for Uncle Joes

***Uncle Joe’s Coffee Club: Frontend (Vue.js)**

This repository contains the customer-facing web application for the Uncle Joe’s Coffee Company pilot. The frontend is built with Vue.js and styled with modern CSS, focusing on a "read-first" experience for menu browsing and member loyalty tracking.

**Tech Stack**

- Framework: Vue.js 3 (Options API)

- Styling: CSS3 (Custom Grid/Flexbox)

- API Communication: Fetch API (Browser Native)

- Hosting: Google Cloud Run (Containerized via Nginx/Apache)

**Key Features and View**

1. Home / Menu:	Browse 30 coffee items and categories.	GET /menu
2. Store Locator:	View addresses for the 485 Midwest locations.	GET /locations
3. Login:	Secure access using the shared pilot password.	POST /auth/login
4. Dashboard: View order history and total points balance. GET /members/me
