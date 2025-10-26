Transparent Bharat - Municipal Fund Tracking System

http://transparentbharath.s3-website-us-east-1.amazonaws.com

A comprehensive web application for transparent tracking of municipal fund allocation and utilization across Indian municipalities. Built with Flask backend and modern Bootstrap frontend.

🚀 Features
🔐 Authentication & User Management
Secure user registration and login system

Profile completion with municipal area mapping

Role-based access control

📊 Dynamic Data Visualization
Real-time Data Streaming: Data loads in batches of 5 records every 1.5 seconds

Interactive Charts: Live updating bar and doughnut charts

Progress Tracking: Visual progress indicator with pause/resume controls

Animated Transactions: Smooth fade-in/out effects for new data

🏗️ Core Modules
Dashboard: Overview of fund allocation and utilization

Projects: Track municipal development projects

Budget: Detailed budget breakdown by departments

Services: Various municipal fund tracking services

Help & Support: Comprehensive help system

💰 Fund Tracking Services
Budget Allocation Tracking

Expenditure Analytics

Project Fund Flow Monitoring

Contract & Tender Tracking

Ward-wise Fund Distribution

Anti-Corruption Watchdog

Participatory Budgeting

Grant & Scheme Tracking

Open Data Portal

🛠️ Technology Stack
Frontend
HTML5 with modern semantic structure

CSS3 with custom Bootstrap 5 theme

JavaScript (ES6+) with dynamic data loading

Bootstrap 5 for responsive design

Chart.js for data visualization

Font Awesome for icons

Backend
Python Flask for REST API

Pandas for Excel data processing

Flask-CORS for cross-origin requests

Data Source
Excel-based municipal fund datasets

Real-time API endpoints

Dynamic data streaming

📥 Installation & Setup
Prerequisites
Python 3.8+

pip (Python package manager)

Modern web browser

Step 1: Clone the Repository
bash
git clone https://github.com/your-username/transparent-bharat.git
cd transparent-bharat
Step 2: Backend Setup
bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Install Python dependencies
pip install flask pandas flask-cors openpyxl
Step 3: Frontend Setup
The frontend is ready to use - no build process required!

Step 4: Data Preparation
Place your Excel file in the project root:

File name: Municipal_Fund_Datasets_Extended.xlsx

Ensure it has columns like: Transaction_ID, Fund_ID, Date, Vendor_Name, Project_Name, Department, Allocated_Amount, Utilized_Amount, Status

Step 5: Run the Application
bash
# Start Flask backend
python app.py

# Open frontend in browser
# Navigate to: http://127.0.0.1:5000/
# Or open index.html directly for frontend-only testing
🎯 Usage
For Citizens
Register/Login: Create an account with your details

Complete Profile: Add your municipal area and location

Explore Dashboard: View real-time fund allocation data

Track Projects: Monitor ongoing and completed projects

Analyze Budget: Understand municipal spending patterns

For Municipal Authorities
Data Upload: Update Excel dataset with latest transactions

Transparency: Provide citizens with real-time fund tracking

Accountability: Monitor fund utilization across departments

Key Interactions
Automatic Data Streaming: Data loads automatically when you open the dashboard

Pause/Resume: Control the data stream with pause/resume buttons

Real-time Updates: Charts and statistics update dynamically

Export Data: Download transaction data in Excel format

📁 Project Structure
text
transparent-bharat/
├── app.py                 # Flask backend server
├── index.html            # Main frontend application
├── Municipal_Fund_Datasets_Extended.xlsx  # Data source
├── README.md             # Project documentation
├── requirements.txt      # Python dependencies
└── assets/              # Static assets (if any)
    ├── css/
    ├── js/
    └── images/
🔧 API Endpoints
GET /api/data
Description: Fetches all municipal fund data

Response: JSON array of transaction records

Usage: Powers the dynamic data loading feature

Data Format
json
{
  "Transaction_ID": "EXP-MUN25-001",
  "Fund_ID": "FND100-MUN25",
  "Date": "2025-09-13",
  "Vendor_Name": "AquaInfra",
  "Project_Name": "Water Pipeline Upgrade",
  "Department": "Water Supply",
  "Allocated_Amount": "10000000",
  "Utilized_Amount": "665159",
  "Status": "Pending"
}
🌟 Key Features in Detail
Dynamic Data Loading
Batch Processing: Loads 5 records at a time

Visual Feedback: Progress bar and counter display

Smooth Animations: Charts and transactions animate on update

User Control: Pause/resume/restart data stream

Responsive Design
Mobile-first approach

Cross-browser compatibility

Accessible interface

Indian color theme (Saffron, White, Green)

Data Security
Client-side data processing

No sensitive data storage

CORS-enabled API

Secure authentication flow

🚀 Deployment
Local Development
bash
python app.py
# Access at: http://127.0.0.1:5000/
Production Deployment
Backend: Deploy Flask app to Heroku, AWS, or similar

Frontend: Host on Netlify, Vercel, or static hosting

Database: Consider migrating from Excel to PostgreSQL

Environment Variables
bash
FLASK_ENV=production
DATABASE_URL=your_database_url
SECRET_KEY=your_secret_key
🤝 Contributing
We welcome contributions! Please follow these steps:

Fork the repository

Create a feature branch (git checkout -b feature/amazing-feature)

Commit your changes (git commit -m 'Add amazing feature')

Push to the branch (git push origin feature/amazing-feature)

Open a Pull Request

Development Guidelines
Follow PEP 8 for Python code

Use semantic HTML5

Ensure responsive design

Add comments for complex logic

Test across different browsers

📊 Performance Features
Lazy Loading: Data streams in batches to prevent overload

Efficient Charts: Chart.js with animation optimizations

Minimal Dependencies: Lightweight library usage

Fast Initial Load: Optimized asset delivery

🎨 Customization
Theming
Modify CSS variables in :root selector:

css
:root {
    --saffron: #FF9933;
    --white: #FFFFFF;
    --green: #138808;
    --blue: #000080;
}
Adding New Services
Update serviceData object in JavaScript

Add corresponding HTML card in services section

Implement service logic in modal handler

📈 Future Enhancements
User authentication with JWT tokens

Database integration (PostgreSQL/MongoDB)

Real-time notifications

Advanced filtering and search

Mobile app development

Multi-language support

Audit trail system

Predictive analytics

🐛 Troubleshooting
Common Issues
CORS Errors: Ensure Flask-CORS is installed and configured

Data Not Loading: Check Excel file path and format

Charts Not Rendering: Verify Chart.js is loaded properly

Authentication Issues: Clear browser localStorage

Debug Mode
Enable console logging by checking browser developer tools for detailed error messages and data flow information.

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
Bootstrap for the responsive frontend framework

Chart.js for beautiful data visualizations

Font Awesome for the comprehensive icon set

Flask for the lightweight Python backend

Indian Government for inspiration in transparency initiatives

📞 Support
For support and queries:

📧 Email: support@transparentbharat.gov.in

📱 Helpline: 1800-123-4567

🐛 Issues: GitHub Issues

Transparent Bharat - Bringing transparency to municipal fund allocation through technology. 🇮🇳

Made with ❤️ for Digital India
