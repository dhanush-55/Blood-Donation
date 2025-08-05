Blood Donation
Welcome to the Blood Donation App repository! This project is a web-based application that connects blood donors directly with individuals in urgent need. It ensures fast, secure, and efficient donor-recipient communication using a reliable database and location-aware features.

Features
Donor Search by Blood Type: Quickly find donors based on required blood group and location.

Direct Contact: Enables recipients to directly reach out to potential donors via secure messaging or contact details.

Donor Registration: Allows users to register as blood donors with key details like name, blood type, phone, and availability.

Admin Panel (Optional): Monitor, verify, and manage blood requests and donor entries.

Technologies Used
Frontend: HTML, CSS

Backend: PHP

Database: MySQL

Icons: FontAwesome

Security: Basic form validations and secure data submission using PHP

Additional Information
The system supports filtering based on blood type (A+, A−, B+, etc.).

Contact information is securely stored and shown only upon user request.

The project can be expanded to include features like donor history, availability tracker, or integration with location APIs for real-time suggestions.

Getting Started
To get a local copy up and running, follow these simple steps:

Prerequisites
A local server (like XAMPP, WAMP, or MAMP) with PHP and MySQL support

A modern web browser

Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/blood-donation-app.git
Navigate to the project directory:

bash
Copy
Edit
cd blood-donation-app
Import the SQL file (if included) to your MySQL database via phpMyAdmin.

Configure the database connection in the PHP files (e.g., config.php) with your DB credentials.

Run your local server and open index.html or index.php in your browser.

Usage
Donors can register by entering their details on the sign-up form.

Recipients can search for donors using blood type and city filters.
