# Uncle-Joes-Frontend-
Vue.js frontend for Uncle Joes

***Uncle Joe’s Coffee Club: Frontend (Vue.js)**

This repository contains the customer-facing web application for the Uncle Joe’s Coffee Company pilot. The frontend is built with Vue.js and styled with modern CSS, focusing on a "read-first" experience for menu browsing and member loyalty tracking.

**Key Features and View**

1. Home / Menu:	Browse 30 coffee items and categories.	GET /menu
2. Store Locator:	View addresses for the 485 Midwest locations.	GET /locations
3. Login:	Secure access using the shared pilot password.	POST /auth/login
4. Dashboard: View order history and total points balance. GET /members/me

<br>

**Tech Stack**

- Framework: Vue.js 3 (Options API)

- Styling: CSS3 (Custom Grid/Flexbox)

- API Communication: Fetch API (Browser Native)

- Hosting: Google Cloud Run (Containerized via Nginx/Apache)

<br>

**Local Development**

1. Clone the Repository: git clone https://github.com/mgmt54500-sp26/uncle-joes-frontend.git
cd uncle-joes-frontend
2. Launch a Local Serve:
   - Python: python -m http.server 8080
   - VS Code: Right-click index.html and select "Open with Live Server"
4. Access the App: Open http://localhost:8080 in your browser.


**Deployment**
- Build the website: The website pages and format are generated through Google AI studio.
- Containerization: The AI-generated assets are packaged into a Docker container, ensuring the frontend remains performant and portable.
- Cloud Run: Deployed as a serverless service, providing an auto-scaling, public URL for Uncle Joe's customers. 
