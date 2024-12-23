# Personal Expense Tracker

## Overview

The Personal Expense Tracker is a Django-based web application designed to help users effectively manage their finances. Users can log daily expenses, categorize them, and access advanced features like automated categorization and future expense predictions. This document provides setup instructions and highlights the application's key features.

## Features

- **Expense Logging**: Record your daily expenses with details like date, description, amount, and category.
- **Automated Categorization**: Leverages machine learning to automatically categorize expenses based on their descriptions.
- **Future Expense Prediction**: Predicts upcoming expenses based on historical spending patterns to aid in budget planning.
- **User Authentication**: Securely manage your account and expenses with a personal login.

## Setup Instructions

Follow these steps to set up and run the application on your local machine:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/personal-expense-tracker.git
   ```

2. **Set Up a Virtual Environment** (optional but recommended):
   ```bash
   python -m venv venv
   ```

3. **Activate the Virtual Environment**:
   - On **Windows**:
     ```bash
     venv\Scripts\activate
     ```
   - On **macOS/Linux**:
     ```bash
     source venv/bin/activate
     ```

4. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

5. **Apply Database Migrations**:
   ```bash
   python manage.py migrate
   ```

6. **Create a Superuser** (for admin access):
   ```bash
   python manage.py createsuperuser
   ```

7. **Run the Development Server**:
   ```bash
   python manage.py runserver
   ```

8. **Access the Application**:
   Open your browser and navigate to `http://localhost:8000`.

## Usage

1. **Sign Up/Login**:
   - Create a user account or log in with your superuser credentials.

2. **Log Expenses**:
   - Click on "Add Expense" and fill in the details such as date, description, amount, and category.
   - Leave the category blank for automated categorization.

3. **View Insights**:
   - Check your expense history, categorized summaries, and future predictions on the dashboard.

4. **Admin Panel**:
   - Visit `http://localhost:8000/admin/` to manage users, categories, and the database.

## Contributing

We welcome contributions to enhance this application. To contribute:

1. **Fork the Repository**:
   - Create a fork on GitHub.

2. **Create a New Branch**:
   ```bash
   git checkout -b feature-name
   ```

3. **Make Changes and Commit**:
   ```bash
   git commit -m "Description of changes"
   ```

4. **Push Changes**:
   ```bash
   git push origin feature-name
   ```

5. **Submit a Pull Request**:
   - Open a pull request on the original repository to propose your changes.

## Acknowledgments

- Special thanks to the Django community for their support and tools.
- The machine learning features were developed using open-source libraries and publicly available datasets.

Feel free to customize and expand this application to suit your needs. Happy expense tracking!

