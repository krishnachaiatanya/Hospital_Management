# Hospital Management System

A comprehensive hospital management system built with Flask.
This website is running at https://hospital-management-7d4n.onrender.com

## Features

- Patient management
- Doctor management
- Appointment scheduling
- Room management for admitted patients
- User authentication (admin and patient roles)
- Responsive design

## Deployment Instructions for Render



1.Set up MySQL database:
   - Go to the Freeonline mysql database
   - Create a new MySQL database
   - Update the .env file with the database credentials:
     ```
     DATABASE_URI=mysql://username:password@hostname/database_name
     ```

2. Run the database initialization script:
   ```bash
   cd ~/hospital
   python init_database.py
   ```


3.Deployment in render:
    --- Upload all your files in render .
    --- Give commands as pip install -r requirements.txt.
    --- Give run command as python app.py.

## Local Development

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Set up environment variables in .env file
4. Run the app: `python app.py`

## License

This project is licensed under the MIT License. 
