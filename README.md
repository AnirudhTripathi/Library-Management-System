# Online Library Management System
This is an online library management system that allows students to access other students' notes and books as per the curriculum. The system is built using PHP, JavaScript, CSS, and PostgreSQL. This README file explains how to set up and use the system.

## Features
The online library management system has the following features:

**User authentication and authorization**
- User registration
- User profile management
- Upload and download of books and notes
- Search and notes by curriculum, subject, and author
- View book and note details, including description, author
- Comment on books and notes
## Requirements
**To run the online library management system, you need the following:**

- PHP 7.4 or later
- PostgreSQL 10 or later

## Installation
**Follow these steps to install the system:**

1. Clone the repository using the following command:
```
git clone https://github.com/AnirudhTripathi/Library-Management-System
```
2. Navigate to the project directory using the following command:
```
cd Library-Management-System
```
3. Create a new PostgreSQL database for the system.
4. Create a copy of the `.env.example` file and rename it to `.env`.
5. Update the .env file with your database details.
6. Run the database migrations using the following command:
```
php artisan migrate
```
7. Generate a new application key using the following command:
```vbnet
php artisan key:generate
```
8. Start the server using the following command:
```
php artisan serve
```
9. Open the system in your web browser at http://localhost:8000.
## Project Structure
```
onlinelibrary/
├── connections/
│   └── connect.php
├── javascript/
│   ├── signin.js
│   └── validation.js
├── styles/
│   ├── assets/
│   │   ├── images/
│   │   └── designs/
│   ├── aboutdesign.css
│   ├── coursedesign.css
│   ├── dashboarddesign.css
│   ├── design.css
│   ├── infodesign.css
│   └── logindesign.css
├── about.php
├── about2.php
├── course.php
├── dashboard.php
├── index.php
├── info.php
├── login.php
├── logout.php
└── signin.php
```
This structure separates the PHP files into the root directory, with supporting files organized in subdirectories based on their type. The `connections/` directory holds the `connect.php` file responsible for connecting to the database. The `javascript/` directory holds the JavaScript files for form validation and user sign-in. The `styles/` directory holds the CSS files for styling the website, with an `assets/` subdirectory for images and designs.
## Usage
**To use the online library management system, follow these steps:**
1. Register for an account on the system.
2. Log in to the system using your email address and password.
3. Upload books and notes by navigating to the "Upload" page.
4. Search and filter books and notes by curriculum, subject, and author using the search bar.
5. View book and note details, including description, author, and publication date, by clicking on the book or note.
6. Comment on books and notes by scrolling to the bottom of the page and entering your comment in the comment box.
7. Update your profile by navigating to the "Profile" page.
## Conclusion
The online library management system is a powerful tool for students to access other students' notes and books as per the curriculum. It is built using PHP, JavaScript, CSS, and PostgreSQL and is easy to install and use. If you have any questions or comments, please feel free to contact us.