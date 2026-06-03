Online Civic Issues Reporting System

Overview

The Online Civic Issues Reporting System is a web-based application developed to help citizens report civic issues such as road damage, water leakage, garbage accumulation, streetlight failures, and other public infrastructure problems. The system enables efficient communication between citizens and government departments, ensuring faster issue tracking and resolution.

Features

User Features

- Email OTP-based secure login
- Submit civic complaints online
- Upload images related to complaints
- Capture and store current location
- Track complaint status using complaint code
- View complaint history
- Submit feedback and ratings

Officer Features

- Secure officer login
- View department-specific complaints
- Update complaint status
- Add remarks and resolution details
- Access complaint location through Google Maps

Admin Features

- Manage officers and departments
- Monitor all complaints
- View system statistics and reports
- Manage user feedback
- Generate complaint summaries

Technology Stack

Frontend

- HTML5
- CSS3
- JavaScript

Backend

- PHP

Database

- MySQL

Libraries & APIs

- PHPMailer (OTP Email Verification)
- Google Maps Integration
- Browser Geolocation API

System Modules

User Module

Handles user authentication, complaint registration, complaint tracking, and complaint history.

Officer Module

Allows officers to view complaints, update statuses, and provide resolution remarks.

Admin Module

Provides complete system administration, officer management, and complaint monitoring.

Feedback Module

Collects user ratings and suggestions for system improvement.

Database Tables

- users
- complaints
- officers
- feedback
- admin

Installation

1. Clone the repository:

git clone https://github.com/yourusername/online-civic-issues-reporting-system.git

2. Move the project folder to:

htdocs/

3. Create a MySQL database:

civic_system

4. Import the provided SQL file.

5. Configure database settings in:

db.php

6. Start Apache and MySQL using XAMPP.

7. Open:

http://localhost/project-folder

Project Workflow

1. User enters email address.
2. OTP is generated and sent via email.
3. User verifies OTP and logs in.
4. Complaint is submitted with description, image, and location.
5. Complaint is assigned to the relevant department.
6. Officer reviews and updates complaint status.
7. User tracks complaint progress.
8. User submits feedback after resolution.

Security Features

- OTP-based authentication
- Session management
- Input validation
- Department-wise access control
- Secure database connectivity

Future Enhancements

- Mobile application support
- AI-based complaint classification
- SMS notifications
- Real-time complaint tracking
- Multi-language support
- Cloud deployment
  
Officer Details 
 
1.rd_admin
2.pass123

admin details

1.admin
2.admin123
