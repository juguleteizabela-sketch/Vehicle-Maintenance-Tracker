# Vehicle-Maintenance-Tracker
"Fisa Auto de Bord" is a CRUD web application designed to help owners manage their vehicle's complete history. It centralizes legal documents, service logs, fuel records, and dashboard errors, ultimately generating a shareable VIN-based "Digital Passport".

## Features
* **User Authentication:** Secure login and registration system.
* **Vehicle Management:** Add, delete, and manage multiple vehicles.
* **Service & Fuel Logs:** Track maintenance records and refueling history.
* **Digital Passport:** Manage digital vehicle passports and essential documents.
* **Dashboard Guide:** Visual guide for dashboard warning lights.
* **Analytics & Alerts:** View statistics and receive notifications.

## Technologies Used
* PHP
* MySQL
* HTML / CSS

## Setup and Installation (WAMP Server)

1. **Start WAMP Server:** Ensure your WAMP server is running (the tray icon should be green).
2. **Add to Workspace:** Copy the project folder into your WAMP directory, usually located at `C:\wamp64\www\`.
3. **Database Setup:**
   * Open your browser and navigate to `http://localhost/phpmyadmin`.
   * Create a new database (e.g., `BazaDeDateMasini`).
   * Go to the **Import** tab and upload the `BazaDeDateMasini.sql` file included in this project.
4. **Configuration:** * Check your database connection file (e.g., `config.php` or `db_connect.php`) and make sure the credentials match your WAMP setup. The default username is usually `root` with no password.
5. **Run the Application:** * Open your browser and go to `http://localhost/your_project_folder_name/login.php`.

## 📄 Documentation Note

Please note that the comprehensive technical documentation file (`Documentatie_Fisa_Auto_de_Bord_Final.docx`) is written in **Romanian**. 

**Role:** This document was developed as part of an academic project for the National University of Science and Technology POLITEHNICA Bucharest. It serves as an in-depth technical guide, detailing the theoretical foundations, complete database schema, security implementations, and the architectural workflow of each module.
