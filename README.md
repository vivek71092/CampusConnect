# CampusConnect: Streamlining College Admissions 🚀

[![GitHub stars](https://img.shields.io/github/stars/YOUR_GITHUB_USERNAME/CampusConnect.svg?style=social)](https://github.com/YOUR_GITHUB_USERNAME/CampusConnect/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/YOUR_GITHUB_USERNAME/CampusConnect.svg?style=social)](https://github.com/YOUR_GITHUB_USERNAME/CampusConnect/network/members)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents
* [Overview](#overview)
* [Features](#features)
    * [For Students](#for-students)
    * [For Administrators](#for-administrators)
* [Technology Stack](#technology-stack)
* [Getting Started](#getting-started)
    * [Prerequisites](#prerequisites)
    * [Installation and Running the Project](#installation-and-running-the-project)
* [Usage](#usage)
    * [For Students](#for-students-1)
    * [For Administrators](#for-administrators-1)
* [Project Structure](#project-structure)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)

---

## Overview

CampusConnect is a comprehensive, web-based **College Admission Management System** meticulously designed to streamline and automate the entire college admission process. This robust platform offers a dual-interface approach: providing prospective students with a user-friendly experience for application submission and tracking, while equipping college administrators with powerful tools for efficient management, evaluation, and communication.

Our primary objectives with CampusConnect are to:
* **Simplify the application journey** for students, making it intuitive, transparent, and less stressful.
* **Automate and optimize administrative tasks**, significantly reducing manual workload, minimizing errors, and accelerating the admissions cycle.
* **Enhance communication channels** between applicants and the college, ensuring timely updates, clear guidance, and a more responsive admissions experience.

---

## Features

CampusConnect offers tailored functionalities for both students and administrators, ensuring a holistic and efficient admission cycle from start to finish.

---

### For Students:

* **Effortless Application Submission:** A guided, step-by-step application form that simplifies the process of submitting academic records, personal details, and other required information.
* **Real-time Application Tracking:** Students gain immediate visibility into their application's journey, with the ability to log in and view live statuses (e.g., `Pending`, `Under Review`, `Admitted`, `Rejected`) on their personalized dashboard.
* **Personalized Dashboard:** A dedicated and intuitive hub displaying a comprehensive application history, critical notifications, and upcoming deadlines, ensuring students are always informed.
* **Secure Document Upload:** A robust and secure system for uploading all necessary supporting documents, such as transcripts, certificates, recommendation letters, and essays.
* **Direct Communication Channel:** Receive instant, personalized messages and official updates directly from the college administration regarding their application progress or any additional requirements.

---

### For Administrators:

* **Centralized Application Management:** A powerful, intuitive dashboard enabling administrators to effortlessly view, filter, sort, and search through all submitted applications, ensuring no application is overlooked.
* **Streamlined Applicant Evaluation:** Dedicated tools to efficiently review applications, assign evaluators, and record detailed evaluation scores and comments, facilitating fair and consistent assessment.
* **Intuitive Admission Decisioning:** Quickly update application statuses (e.g., `Admit`, `Reject`, `Waitlist`) with a few clicks, automatically triggering pre-configured email notifications to inform students of their outcome.
* **Insightful Reporting & Analytics:** Generate valuable, data-driven reports on application trends, admission rates, demographic breakdowns, and other key metrics to inform strategic decision-making and improve future admission cycles.
* **Robust User Management:** Securely manage administrator accounts, define roles, and assign granular permissions, ensuring data integrity and operational security.
* **Integrated Communication Hub:** Send mass notifications to all applicants or craft individualized messages directly from the platform, streamlining outreach and ensuring consistent communication.

---

## Technology Stack

CampusConnect is built using a reliable, widely adopted, and robust set of web technologies, ensuring stability, performance, and maintainability:

* **Frontend:** HTML, CSS, JavaScript (for creating dynamic, responsive, and user-friendly interfaces)
* **Backend:** PHP (for powerful server-side logic, data processing, and API management)
* **Database:** MySQL (for efficient, scalable, and secure data storage and retrieval)

---

## Getting Started

Follow these comprehensive steps to set up and run CampusConnect on your local development environment.

### Prerequisites

To successfully run CampusConnect, you'll need a local server environment that includes **Apache** (as a web server) and **MySQL** (as a database server). We highly recommend using one of the following all-in-one packages:

* **XAMPP:** For Windows and Linux users.
* **WAMP:** Specifically for Windows users.
* **MAMP:** Specifically for macOS users.

**Important:** Before proceeding with the installation, ensure that both the **Apache** and **MySQL** services are actively running from your chosen local server's control panel.

### Installation and Running the Project

1.  **Clone the Repository:**
    Navigate to your local server's web root directory, typically named `htdocs`.
    * **Windows (XAMPP):** `C:\xampp\htdocs\`
    * **macOS (XAMPP):** `/Applications/XAMPP/htdocs/`
    * **Linux (Apache):** `/var/www/html/`

    Once in the `htdocs` directory, clone the CampusConnect repository into a new folder named `cams`:

    ```bash
    git clone [https://github.com/vivek71092/CampusConnect.git](https://github.com/vivek71092/CampusConnect.git) cams
    ```
    *If you've previously cloned the repository to a different location, simply move the `CampusConnect` folder into your `htdocs` directory and rename it to `cams`.*

2.  **Database Setup:**
    * Open your web browser and navigate to `http://localhost/phpmyadmin` to access the phpMyAdmin interface.
    * In phpMyAdmin, create a new database. Name this database `camsdb`.
    * From the left sidebar, select the newly created `camsdb` database.
    * Go to the "**Import**" tab located in the top navigation bar.
    * Click the "**Choose File**" button and select the `camsdb.sql` file. This file is located within the `database` folder of your cloned project (e.g., `cams/database/camsdb.sql`).
    * Click the "**Go**" button at the bottom of the page to import the SQL schema and initial data into your `camsdb` database.

3.  **Access the Application:**
    With Apache and MySQL services running and the database successfully imported, open your web browser and navigate to the following URL to access the CampusConnect application:

    ```
    http://localhost/cams
    ```

---

## Usage

CampusConnect provides distinct user experiences tailored for both prospective students and college administrators.

---

### For Students:

1.  **Access the Application:** Open your web browser and go to `http://localhost/cams`.
2.  **Register an Account:** Click on the "Register" or "Sign Up" link to create a new student account. Provide the required personal details to set up your profile.
3.  **Log In:** Use your newly registered credentials to log into your student dashboard.
4.  **Complete Application:** Navigate to the application section and meticulously fill out the step-by-step application form, providing all necessary academic, personal, and extracurricular information.
5.  **Upload Documents:** Securely upload all required supporting documents (e.g., transcripts, certificates, recommendation letters) as specified by the college.
6.  **Monitor Progress:** Regularly check your personalized dashboard to view your application's real-time status, receive important notifications, and keep track of upcoming deadlines.

---

### For Administrators:

1.  **Access the Application:** Open your web browser and go to `http://localhost/cams`.
2.  **Log In:** Use the designated administrator credentials to access the administrative portal.
    * **Default Admin Username:** `admin`
    * **Default Admin Password:** `password`
    * ***Security Note:*** *For any production deployment or in a shared environment, it is **critically important** to change these default credentials immediately after the initial setup to ensure the security of the system.*
3.  **Manage Applications:** From the admin dashboard, you can view, filter, sort, and search through all submitted applications.
4.  **Evaluate Candidates:** Utilize the evaluation tools to review applicant profiles, assign evaluators, record scores, and add comments.
5.  **Make Decisions:** Easily update application statuses (e.g., `Admit`, `Reject`, `Waitlist`) and trigger automated notifications to applicants.
6.  **Generate Reports:** Access reporting and analytics features to gain insights into application trends, admission rates, and other key metrics.

---

## Project Structure

The CampusConnect project is organized into a clear and logical directory structure to enhance readability, maintainability, and collaboration:
