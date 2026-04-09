🚀 Productivity Tracker Chrome Extension
📌 Internship Project

Company: CODTECH IT SOLUTIONS

Name: APEKSHA RAJU CHAVAN

Intern ID: CTIS5239

Domain: Full Stack Web Development

Duration: 12 Weeks

Mentor: Neela Santosh Kumar

________________________________________
📖 Project Description
The Productivity Tracker Chrome Extension is a browser extension designed to monitor and analyze the amount of time users spend on different websites. The extension automatically tracks active browser tabs and sends usage data to a backend server.
The backend is developed using Django, which stores the browsing data and allows administrators to analyze productivity patterns.
This project helps users understand their browsing habits and improve productivity by identifying time spent on various websites.

________________________________________
⚙️ Technologies Used
Frontend
•	HTML
•	JavaScript
•	Chrome Extension APIs
Backend
•	Django
•	Python
•	SQLite Database
Tools
•	Chrome Developer Mode
•	VS Code
•	Postman
________________________________________
🏗️ Project Architecture
Chrome Extension → Django API → Database → Admin Dashboard
1.	Chrome extension tracks active website.
2.	Time spent on the website is recorded.
3.	Data is sent to Django backend via API.
4.	Django stores data in database.
5.	Admin panel displays tracked website data.
________________________________________

📁 Project Structure
productivity_tracker_project
productivity_backend
│
├── productivity_backend
│ ├── settings.py
│ ├── urls.py
│
├── tracker
│ ├── models.py
│ ├── views.py
│ ├── urls.py
│ ├── admin.py
chrome_extension
│
├── manifest.json
├── background.js
├── popup.html
└── popup.js
________________________________________
🚀 Installation Guide
1️⃣ Clone the repository
git clone https://github.com/your-username/productivity-tracker.git
cd productivity-tracker
________________________________________
2️⃣ Install Dependencies
pip install django
pip install django-cors-headers
________________________________________
3️⃣ Run Django Server
cd productivity_backend
python manage.py migrate
python manage.py runserver
Server will start at:
http://127.0.0.1:8000
________________________________________
4️⃣ Load Chrome Extension
1.	Open Chrome
2.	Go to:
chrome://extensions/
3.	Enable Developer Mode
4.	Click Load unpacked
5.	Select chrome_extension folder
________________________________________
📊 Features
✅ Tracks active website tabs
✅ Records time spent on websites
✅ Sends browsing data to Django backend
✅ Stores productivity data in database
✅ Admin dashboard to monitor tracked websites
________________________________________
📸 Example Output
Django Console Output
Website: https://github.com
Time Spent: 10
Website: https://youtube.com
Time Spent: 15
________________________________________
🔐 Admin Dashboard
Admin dashboard allows administrators to:
•	View tracked websites
•	Monitor user activity
•	Analyze browsing time
Access admin panel:
http://127.0.0.1:8000/admin
________________________________________
📈 Future Improvements
•	Productivity analytics dashboard
•	Website category classification
•	Charts for time analysis
•	Weekly productivity reports
•	AI-based productivity scoring
________________________________________
🎯 Conclusion
This project demonstrates the integration of Chrome Extensions with a Django backend to build a productivity monitoring system. It provides valuable insights into browsing behavior and helps improve user productivity.
________________________________________

👨‍💻 Author
APEKSHA RAJU CHAVAN
Full Stack Web Development Intern
CODTECH IT SOLUTIONS

