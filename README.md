# COLLEGE-ERP
College ERP System
Welcome to the College ERP System repository! This project is a comprehensive web-based solution designed to streamline and manage various aspects of a college's operations, including student registration, academic records management, and family information tracking.

Features

Student Registration: Users can register new students by providing basic information such as registration number and mobile number. The system generates an OTP for authentication.
Academic Records Management: Keep track of students' academic performance over multiple years, including attendance percentage, assignment marks, and project marks.
Student Details: Store detailed information about students, including images, family information, and other relevant data.
Secure OTP Verification: Utilizes one-time passwords (OTP) for secure student authentication during the login process.
Responsive Design: The system is built using Bootstrap CSS framework, ensuring a responsive and visually appealing user interface across different devices and screen sizes.

Technologies Used

Django: A high-level Python web framework used for rapid development of web applications. Django provides built-in tools for URL routing, form handling, and database ORM.
MySQL: A robust relational database management system used for storing and managing student data, academic records, and other information.
HTML/CSS/JavaScript: Front-end technologies used for creating the user interface and enhancing interactivity.
Bootstrap: A popular CSS framework for building responsive and visually appealing web interfaces. Bootstrap provides a set of pre-designed components and styles for faster development.
GitHub: Version control system used for managing the project's source code, facilitating collaboration among team members, and tracking changes over time.

Getting Started
To get started with the College ERP System, follow these steps:

Clone the Repository: Use the following command to clone the repository to your local machine:
git clone https://github.com/your-username/college-erp.git

Install Dependencies: Navigate to the project directory and install the required dependencies using the following command:
pip install -r requirements.txt

Set Up Database: Configure the MySQL database settings in the settings.py file. Run migrations to create the necessary database tables:
python manage.py makemigrations
python manage.py migrate

Run the Server: Start the Django development server to run the College ERP System locally:
python manage.py runserver

Access the Application: Open a web browser and navigate to http://localhost:8000 to access the College ERP System.
