🌿 EcoTrack Vision – Campus Sustainability Portal

📌 Project Overview

EcoTrack Vision is a smart campus sustainability and environmental monitoring web portal designed to help educational institutions identify, report, monitor, and manage common campus issues such as water leakage, overflowing dustbins, unnecessary electricity usage, and other visible environmental problems.

The platform provides a centralized dashboard where students, faculty, maintenance staff, and administrators can interact with campus sustainability activities. Users can report issues by selecting the campus area, describing the problem, and uploading an image. The system also provides an AI monitoring concept for authorised common campus areas and allows campus resource readings such as water and electricity consumption to be recorded.

The project is developed as a prototype/MVP, with AI detection currently represented through simulated demo events.

---

🎯 Problem Statement

Educational campuses generate different types of environmental and resource-management problems every day, including:

- Water leakage and unnecessary water wastage
- Overflowing dustbins and improper waste management
- Lights and fans being left on unnecessarily
- Difficulty in tracking reported campus issues
- Lack of centralized sustainability monitoring
- Delayed communication between users and maintenance staff
- Difficulty in maintaining resource consumption records

EcoTrack Vision provides a centralized digital platform to make these issues easier to report, monitor, and manage.

---

💡 Proposed Solution

EcoTrack Vision combines a campus dashboard, issue reporting system, photo-based reporting, role-based access interface, monitoring concept, resource readings, and sustainability recommendations into one web application.

Users can report a visible campus issue, attach a photo, select its location and problem type, and create a report. Reports can then be tracked through different statuses such as Open, In Progress, and Resolved.

---

✨ Key Features

1. 🔐 Login & Sign Up System

The application provides authentication screens with:

- Log In option
- Sign Up option
- Campus email field
- Password field
- Full name field during registration
- Role selection
- User role
- Maintenance role
- Admin role
- Admin passcode field during Admin registration
- Logout functionality

The logged-in user's role and email are displayed in the dashboard header.

---

2. 👥 Role-Based Interface

The system supports three different roles:

👨‍🎓 User

For students/faculty members who can:

- Report campus issues
- Upload issue photographs
- View recent reports
- Monitor sustainability information
- Record resource readings

🛠️ Maintenance

For campus maintenance staff who can:

- View reported issues
- Track issue status
- Update reports from Open to In Progress or Resolved

👨‍💼 Admin

For system administrators who can manage the overall sustainability portal.

«Note: The current prototype provides the role-selection interface; a real backend-based permission system would be required for production-level authorization.»

---

3. 📊 Campus Eco Dashboard

After login, users are taken to the main Campus Eco Dashboard.

The dashboard provides quick information about campus sustainability activities.

It includes:

- Total reports
- Open alerts
- Resolved reports
- Areas covered

The statistics automatically update according to the report data available in the application.

---

4. 📸 Campus Issue Reporting

Users can report visible campus problems through a dedicated reporting form.

The user can select:

Campus Area

- Washroom
- Computer Lab
- Classroom
- Hostel
- Canteen
- Garden
- Other

Suspected Problem

- Water leakage / water on floor
- Tap may be left running
- Overflowing dustbin / litter
- Lights or fans left on
- Other visible issue

Users can also provide additional details about the problem.

---

5. 🖼️ Image Upload & Preview

The reporting system allows users to upload an image of the reported issue.

Supported image formats include:

- JPG
- PNG
- WEBP

After selecting an image, the application displays a preview of the uploaded photograph before submitting the report.

---

6. 🤖 AI Monitoring Centre

The application includes an AI Monitoring Centre concept for authorised common campus areas.

Monitoring areas include:

- Computer Lab
- Classroom
- Corridor
- Canteen common area
- Garden path
- Hostel common area

The interface contains:

- Monitoring status
- Live monitoring indicator
- Camera-style monitoring screen
- Privacy filter indicator
- Event monitoring interface
- Start auto-detection demo button
- Stop monitoring button
- Sample event display

The current version uses simulated AI monitoring events as a prototype.

---

7. 🔒 Privacy-Aware Monitoring Concept

The monitoring interface includes a:

"PRIVACY FILTER: ON"

indicator and restricts the monitoring concept to authorised common campus areas.

The application also specifically warns users:

«Never install or use cameras in washrooms.»

This demonstrates the project's focus on responsible and privacy-aware campus monitoring.

---

8. 🗂️ Recent Reports Management

The dashboard displays recently reported campus issues.

Each report contains:

- Problem description
- Campus area
- Priority/severity
- Current status
- Report time
- Status update option

Reports can have three statuses:

- 🟠 Open
- 🔵 In Progress
- 🟢 Resolved

The status can be changed directly from the dashboard.

---

9. 🚦 Issue Priority / Severity

Reports contain priority levels such as:

- Low
- Medium
- High

This can help campus authorities identify which issues require faster attention.

---

10. 📈 Dynamic Dashboard Statistics

The dashboard dynamically calculates:

Total Reports

Number of reports available.

Open Alerts

Number of reports that are not yet resolved.

Resolved

Number of reports marked as resolved.

This allows the dashboard to reflect changes when report statuses are updated.

---

11. 💧 Resource Readings

The platform provides a section for recording campus resource consumption.

Currently supported resources include:

- Water — litres
- Electricity — kWh

Users can enter the current meter reading and save it through the dashboard.

This creates a foundation for future resource-consumption analytics.

---

12. 🌱 Eco Action Suggestions

The system provides simple sustainability recommendations.

🚰 Save Water

Repair leaking taps and report running flushes quickly.

💡 Save Electricity

Switch off unnecessary lights and fans in unused rooms.

♻️ Reduce Waste

Empty overflowing bins and encourage proper waste segregation.

---

13. 📱 Responsive Design

The interface is designed to work across different screen sizes.

Responsive CSS is included for smaller screens so that:

- Dashboard columns adjust automatically
- Statistics cards become mobile-friendly
- Content changes from two-column to single-column layout

---

14. 🎨 Modern User Interface

The application uses a clean green sustainability-themed interface.

UI features include:

- Green environmental color theme
- Dashboard cards
- Rounded panels
- Status badges
- Upload area
- Monitoring screen
- Responsive layout
- Icons and visual indicators
- Interactive buttons
- Form validation

---

🛠️ Technologies Used

Frontend

- HTML5
- CSS3
- JavaScript

HTML5 Features

- Semantic structure
- Forms
- File input
- Image preview
- Select menus
- Responsive viewport

CSS3 Features

- CSS Variables
- Flexbox
- CSS Grid
- Responsive Media Queries
- Gradients
- Animations
- Cards
- Buttons
- Status badges
- Responsive layout

JavaScript Features

- DOM manipulation
- Event handling
- Form handling
- Role selection
- Login/Signup interface switching
- Dynamic report rendering
- Report status updates
- Image preview
- Dashboard statistics
- Monitoring interaction

---

🔄 Project Workflow

User Opens Website
        ↓
Login / Sign Up
        ↓
Select User Role
        ↓
Enter Campus Credentials
        ↓
Campus Eco Dashboard
        ↓
 ┌───────────────┬────────────────┐
 ↓               ↓                ↓
Report Issue   AI Monitoring   Resource Reading
 ↓               ↓                ↓
Upload Photo   Monitor Demo     Save Reading
 ↓
Create Report
 ↓
Recent Reports
 ↓
Update Status
 ↓
Open → In Progress → Resolved

---

📁 Main Project Components

EcoTrack-Vision/
│
├── index.html
│
└── README.md

The current prototype is implemented primarily inside a single HTML file containing:

- HTML structure
- CSS styling
- JavaScript functionality

For a larger production application, these components can later be separated into:

EcoTrack-Vision/
│
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── assets/
│   └── images/
├── README.md
└── LICENSE

---

🚀 Future Scope

The current application is a prototype. It can be expanded with:

- Real AI image classification
- Computer vision-based waste detection
- Real-time camera monitoring
- Waste-type classification
- Automatic severity detection
- Real backend authentication
- Database integration
- Cloud image storage
- Real-time notifications
- Maintenance staff assignment
- Admin control panel
- Campus-wise analytics
- Water consumption graphs
- Electricity consumption graphs
- Waste generation analytics
- Monthly sustainability reports
- Data visualization
- QR-based issue reporting
- Mobile application
- IoT sensors for water/electricity monitoring
- Google Maps/campus map integration
- Automated alerts for high-priority issues

---

🌍 Impact

EcoTrack Vision aims to help educational institutions move toward smarter and more sustainable campus management by:

- Reducing water wastage
- Reducing unnecessary electricity consumption
- Improving waste management
- Making issue reporting easier
- Improving communication with maintenance teams
- Encouraging students and staff to participate in sustainability
- Providing centralized campus sustainability information

---

⚠️ Prototype Limitation

This version is a frontend prototype/MVP.

The AI monitoring and analysis features are simulated and do not represent a production AI model. Login/signup information is also handled on the client side and does not provide real secure authentication.

A backend, database, secure authentication system, and real AI/Computer Vision model would be required for deployment in a real campus environment.

---

📌 Project Status

Status: Prototype / MVP

Domain: AI + Sustainability + Smart Campus + Waste & Resource Management

Target Users: Students, Faculty, Maintenance Staff and Campus Administrators

Primary Goal: Smart and sustainable campus monitoring and issue management.
