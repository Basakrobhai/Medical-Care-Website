# Medical Care Management System

## Overview

The Medical Care Management System is a Python-based application designed to manage healthcare-related operations including patient records, staff coordination, and administrative workflows. It provides a structured role-based system for administrators, medical staff, and patients with a graphical user interface.

The project is intended for educational purposes and demonstrates concepts such as modular programming, user authentication, data management, and GUI development.

## Features

- User login and authentication system
- Role-based dashboards for different users
- Patient record management
- Staff management and assignment
- Administrative controls and reporting features
- Data storage using JSON files
- Automatic backup system for data safety
- Graphical user interface for interaction

## Project Structure
```
Medical-Care-Website-main/
├── GP_G25/
│   ├── main.py
│   ├── app/
│   ├── gui/
│   ├── data/
│   ├── carelog.log
├── README.md
```
## Requirements

- Python 3.10 or later

## Installation and Setup

1. Download or clone the repository
   git clone https://github.com/your-username/your-repo-name.git

2. Navigate into the project directory
   cd Medical-Care-Website-main/GP_G25

3. (Optional) Create a virtual environment
   python -m venv venv

   Activate it:
   Windows:
   venv\Scripts\activate

   Mac/Linux:
   source venv/bin/activate

4. Install dependencies (if a requirements file exists)
   pip install -r requirements.txt

   If no requirements file is present, the project uses standard Python libraries and no extra installation is required.

## How to Run the Project

1. Open a terminal in the GP_G25 directory

2. Run the main file
   python main.py

3. The application will launch with a graphical user interface

## How It Works

- The system starts by initializing core modules and loading stored data
- Users are required to log in based on their role
- After login, the system loads a role-specific dashboard
- All updates to patients, staff, and system data are saved automatically
- Backup files are generated to prevent data loss

## Data Storage

- All persistent data is stored in the data folder
- Backup copies are stored inside a backups directory within data
- System logs are recorded in carelog.log for debugging and tracking

## Notes

- This is a local desktop application, not a hosted web application
- Ensure Python is installed and added to system PATH before running
- Do not delete the data or backup folders as they are required for correct operation

## Future Improvements

- Conversion into a full web-based system using frameworks such as Flask or Django
- Integration with a relational database (MySQL or PostgreSQL)
- Improved authentication and security systems
- Enhanced UI design and user experience improvements
- Deployment support for cloud hosting

## License

This project is intended for educational use only
