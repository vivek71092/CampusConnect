# CampusConnect: College Admission Management System

## Overview
CampusConnect is a comprehensive web-based platform designed to streamline and automate the college admission process. This system provides a user-friendly interface for prospective students to apply, track their applications, and view admission statuses. Simultaneously, it offers college administrators powerful tools to manage applications, conduct evaluations, and communicate with applicants efficiently.

---

## Features

### For Students
* **Easy Application Submission**: A straightforward, step-by-step application form to submit academic and personal details.
* **Application Tracking**: Students can log in to view the real-time status of their applications (e.g., pending, under review, admitted, rejected).
* **Personalized Dashboard**: A dedicated dashboard showing application history, important notifications, and upcoming deadlines.
* **Document Upload**: Securely upload required documents like transcripts, certificates, and recommendation letters.
* **Communication**: Receive direct messages and updates from the college administration regarding their application.

### For Administrators
* **Application Management**: Centralized dashboard to view, filter, and sort all submitted applications.
* **Applicant Evaluation**: Tools to review applications, assign evaluators, and record evaluation scores and comments.
* **Admission Decisioning**: Easily update application statuses (admit, reject, waitlist) and trigger automated notifications to students.
* **Reporting & Analytics**: Generate reports on application trends, admission rates, and other key metrics.
* **User Management**: Manage administrator accounts, roles, and permissions.
* **Communication Hub**: Send mass notifications or individualized messages to applicants.

---

## Technology Stack

* **Frontend**: HTML, CSS, JavaScript
* **Backend**: PHP
* **Database**: MySQL

---

## Getting Started

### Prerequisites
* **XAMPP/WAMP/MAMP**: You'll need a local server environment (like XAMPP for Windows/Linux, WAMP for Windows, or MAMP for macOS) that includes **Apache** and **MySQL**.

### Installation and Running the Project

1.  **Clone the Repository:**
    Navigate to your local server's `htdocs` directory (e.g., `C:\xampp\htdocs\` on Windows, `/Applications/XAMPP/htdocs/` on macOS, or `/var/www/html/` on Linux for Apache) and clone the `CampusConnect` repository into a folder named `cams`.

    ```bash
    git clone [https://github.com/vivek71092/CampusConnect.git](https://github.com/vivek71092/CampusConnect.git) cams
    ```
    *If you've already cloned it elsewhere, simply move the `CampusConnect` folder into your `htdocs` directory and rename it to `cams`.*

2.  **Database Setup:**
    * Open your web browser and go to `http://localhost/phpmyadmin` to access phpMyAdmin.
    * Create a new database named `camsdb`.
    * Select the `camsdb` database.
    * Go to the "**Import**" tab.
    * Click "**Choose File**" and select the `camsdb.sql` file located in the `database` folder of your cloned project (`cams/database/camsdb.sql`).
    * Click "**Go**" to import the SQL file.

3.  **Start Apache and MySQL:**
    Ensure that both **Apache** and **MySQL** services are running from your XAMPP/WAMP/MAMP control panel.

4.  **Access the Application:**
    Open your web browser and navigate to:
    ```
    http://localhost/cams
    ```

---

## Usage

### For Students
1.  Navigate to the application URL (`http://localhost/cams`).
2.  Register for a new student account.
3.  Log in and fill out the application form.
4.  Upload required documents.
5.  Monitor your application status on your dashboard.

### For Administrators
1.  Navigate to the application URL (`http://localhost/cams`).
2.  Log in with the provided administrator credentials (if you have default ones, consider adding them here, e.g., "Default Admin Username: `admin`, Default Admin Password: `password`").
3.  Access the admin dashboard to manage applications, evaluate candidates, and make admission decisions.

---

## Contributing

We welcome contributions to CampusConnect! If you have suggestions for improvements or want to report a bug, please open an issue on the GitHub repository.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contact

Vivek Kumar - vivek.kumar@example.com (Feel free to replace this with your actual university email or a dedicated project contact email if you're comfortable.)
