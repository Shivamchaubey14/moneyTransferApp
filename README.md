# Banking Application - Django Project

Welcome to the **Banking Application**, a project built using the **Django framework**. This web application simulates the functionalities of a real-world banking system, allowing users to create accounts, manage funds, send payments, and more, all while ensuring security with advanced authentication and encryption features.

This project was developed as part of a **cutting-edge Django course** focused on teaching advanced web development. The course covers everything from setting up the environment to deploying the final application. In this README, you’ll find instructions to get the project running on your local machine.

## Features
- **Robust Authentication**: User login, registration, and password management.
- **KYC Verification**: Implement advanced KYC (Know Your Customer) verification.
- **Transaction Management**: Send and receive payments, link virtual credit/debit cards, and more.
- **Secure Payment Integration**: Two-factor authentication, OTP-based verification, and JWT-based security.
- **Notification System**: Stay informed with real-time notifications for account activities.
- **Responsive UI**: Built with modern, mobile-friendly layouts.

## Tech Stack
- **Backend**: Django, Django REST Framework
- **Frontend**: HTML, CSS, JavaScript
- **Database**: PostgreSQL
- **Hosting**: Railway Hosting, AWS S3 for static and media files
- **Payment Integration**: Razorpay

## Prerequisites
- **Python** version 3.9
- **PostgreSQL** for database management
- Basic knowledge of Django and Python
- Installed **pip** for managing Python packages

## Setup Instructions

### Step 1: Clone the Project
First, clone this repository to your local machine using the following command:

```bash
git clone https://github.com/Shivamchaubey14/moneyTransferApp.git
cd moneyTransferApp/PythonFinalProject
```

### Step 2: Set up a Virtual Environment (Optional)
It's recommended to use a virtual environment for Python projects to manage dependencies. You can set one up with:

```bash
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
```

### Step 3: Install Required Packages
After cloning the project, install all the necessary dependencies listed in the `requirements.txt` file using the command:

```bash
pip install -r requirements.txt
```

Make sure you are using Python 3.9 to avoid compatibility issues.

### Step 4: Database Migrations
Before running the application, you'll need to migrate the database to set up the necessary tables. Run the following commands:

```bash
python manage.py makemigrations
python manage.py migrate
```

### Step 5: Create a Superuser (Admin Access)
To access the Django admin panel and manage your application, you’ll need to create a superuser:

```bash
python manage.py createsuperuser
```

Follow the prompts to set up a username, email, and password.

### Step 6: Run the Development Server
You’re now ready to run the project locally. Start the development server with:

```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your browser to view the application running on your localhost.

### Step 7: Access Admin Panel
The Django admin panel can be accessed at:

```bash
http://127.0.0.1:8000/admin/
```

Use the superuser credentials you created earlier to log in.

## Deployment
This project has been deployed using **Railway Hosting** and **AWS S3** for static and media files. If you want to deploy the app, follow the steps below:

1. Provision a **PostgreSQL** database on Railway.
2. Set up your **AWS S3** bucket for static and media files.
3. Update your `settings.py` file with the necessary environment variables for database and storage.
4. Deploy your project live.

## Additional Features in Development
- **Transaction History**: Track all transactions made by users.
- **Invoice Generation**: Automatically generate downloadable invoices after transactions.
- **Improved Security**: Ongoing work on enhancing encryption and securing API endpoints.

## Contribution
Feel free to contribute to this project by forking the repository and submitting pull requests. All contributions are welcome!

---

This enhanced README provides clear instructions, highlights key features, and makes your project more professional and easy to understand for others!
