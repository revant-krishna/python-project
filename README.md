# Blood Donation Application

A web-based blood donation management system built with Flask that connects blood donors with recipients.

## Features

- User registration and authentication
- Blood donor profile management
- Blood donation tracking
- Search for blood donors by blood group and location
- Donation history tracking
- Modern and responsive UI

## Installation

1. Install Python 3.7 or higher
2. Install required packages:
   ```
   pip install -r requirements.txt
   ```

3. Run the application:
   ```
   python app.py
   ```

4. Open your browser and navigate to `http://localhost:5000`

## Usage

1. Register as a new user by providing your details including blood group
2. Login to your account
3. Update your profile with your contact information and location
4. Search for blood donors when needed
5. Track your donation history

## Project Structure

- `app.py`: Main Flask application file
- `templates/`: Contains HTML templates
- `static/`: Contains CSS and other static files
- `requirements.txt`: List of required Python packages

## Technologies Used

- Flask (Python web framework)
- Flask-SQLAlchemy (Database ORM)
- Flask-Login (User authentication)
- Bootstrap 5 (Frontend framework)
- SQLite (Database)
