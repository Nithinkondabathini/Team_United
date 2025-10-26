Transparent Bharat – Municipal Fund Tracking System

🔗 transparentbharath.s3-website-us-east-1.amazonaws.com

A modern web platform for transparent tracking of municipal funds — from allocation to utilization — across Indian cities. Built using Flask (Python) for the backend and Bootstrap 5 for the frontend.

🚀 Core Features

Secure Login & User Roles: Citizen and municipal-level access with area mapping.

Dynamic Dashboard: Real-time fund data loads in batches every 1.5 seconds.

Interactive Charts: Auto-updating bar and doughnut charts powered by Chart.js.

Progress Tracking: Visual progress bars with pause/resume controls.

Smooth Animations: Transactions fade in/out for real-time updates.

🏗️ Modules

Dashboard: Overview of fund allocation and usage.

Projects: Track project progress and status.

Budget: Detailed breakdown by department.

Services: Includes anti-corruption, participatory budgeting, and open data portal.

Help & Support: FAQs and contact assistance.

💰 Fund Tracking Services

Budget & Expenditure analytics

Project fund flow monitoring

Tender and contract tracking

Ward-wise fund distribution

Anti-corruption watchdog

Grant & scheme tracking

Participatory budgeting

Open data and transparency reports

🛠 Tech Stack

Frontend: HTML5, CSS3 (Bootstrap 5), JavaScript (ES6), Chart.js, Font Awesome
Backend: Python Flask (REST API), Pandas (Excel data), Flask-CORS
Data Source: Excel datasets with real-time API endpoints

📊 Highlights

Auto Data Streaming: 5 records load every 1.5 seconds

Progress Indicators: Live visual stats & charts

Responsive UI: Works on all devices

Secure: CORS-enabled API, no sensitive data stored

Export: Download fund data to Excel

🧩 Deployment

Local: python app.py → open http://127.0.0.1:5000/

Production: Flask backend on AWS/Heroku; frontend on Netlify/Vercel

Database (Future): PostgreSQL or MongoDB

📈 Performance & Future Upgrades

Lazy loading, optimized charts, minimal dependencies

Upcoming: JWT login, database integration, live notifications, multilingual UI, audit trail & predictive analytics

💡 Customization

Update color themes via CSS variables

Add new municipal services by editing JS objects and modals.
