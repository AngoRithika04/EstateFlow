# EstateFlow: A Real Estate Management System

## Project Overview
EstateFlow is a **web-based application** developed using **PHP** and **MySQL** to streamline property management for **real estate agencies, agents, property owners, and buyers**.  
It simplifies **buying, selling, and renting** properties by providing a **centralized platform** for property listings, enquiries, document management, and client communication.

---

## Features
- **Role-Based Access Control**
  - **Admin:** Manage users, approve listings, handle reviews.
  - **Property Owner/Agent:** Add, update, delete property listings, manage enquiries.
  - **Buyer:** Browse/search properties, submit enquiries.
- **Property Management** – Add detailed property info, upload images/documents.
- **Enquiry Handling** – Receive, view, and respond to property enquiries.
- **EMI Calculator** – Calculate loan EMI based on property price and interest rate.
- **Review & Feedback System** – Admin moderates property reviews.
- **Secure Authentication** – Session-based login with hashed passwords.
- **Real-Time Updates** – Instant changes visible to all authorized users.

---

## 🖥️ Tech Stack
| Layer      | Technology |
|------------|------------|
| **Frontend** | HTML, CSS, JavaScript |
| **Backend**  | PHP |
| **Database** | MySQL |
| **Server**   | Apache HTTP Server |
| **IDE**      | Sublime Text |

---

##  Modules Implemented
1. **User Management** – Login, Registration, Logout
2. **Property Management** – Add, Update, Delete properties
3. **Enquiry Management** – Buyer-to-Agent/Owner communication
4. **EMI Calculator**
5. **Review Management**
6. **Admin Dashboard**

---

## System Architecture
EstateFlow follows a **Client-Server Architecture**:
- **Frontend**: Handles the user interface.
- **Backend**: Business logic implemented in PHP.
- **Database**: MySQL stores property, user, and enquiry data.
- **Server**: Apache handles HTTP requests.

---

## Prerequisites
- PHP (>=7.4)
- MySQL
- Apache Server (XAMPP/WAMP/LAMP)
- Web Browser

## How to run EstateFlow in PHP
1. Download the zip file
2. Extract the file and copy the folders and files
3. Paste inside root directory(for xampp xampp/htdocs, for wamp wamp/www, for lamp var/www/html)
4. Open PHPMyAdmin (http://localhost/phpmyadmin)
5. Create a database with name remsdb
6. Import remsdb.sql file(given inside the zip package)
7.Run the script http://localhost/rems

---

# Login Detail for admin
Username : admin
Password: Test@123

# Login Details for Broker/Agent
Username : test@gmail.com
Password: Test@123

# Login Details for Simple User
Username : testuser2@gmail.com
Password: Test@123

Note : Broker and owner module have same features

# Future Enhancements
- Mobile App version for better accessibility
- AI-based property recommendations
- Payment gateway integration
- Map-based property search
- Real-time analytics dashboard
