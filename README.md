# 🌍 Carbon Emission Tracker

<div align="center">
  
[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Flask](https://img.shields.io/badge/Flask-2.3-000000?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)](https://sqlite.org)

</div>

A modern web application for tracking and reducing carbon footprints with dual-mode functionality for individuals and industries.

## ✨ Key Features

### 👤 Individual Mode
- Personal carbon footprint tracking
- Monthly emission reports
- Reduction tips and goals

### 🏭 Industry Mode  
- Multi-department emission tracking
- Bulk CSV data import
- Scope 1/2/3 categorization
- Team collaboration tools

### 🔒 Security
- Password reset via OTP.
- Role-based access control.
- Data isolation between users.

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- pip package manager

### Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/carbon-emission-tracker.git
cd carbon-emission-tracker

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
# venv\Scripts\activate   # Windows

# Install dependencies
pip install -r requirements.txt

# Configure environment
cp .env.example .env
nano .env  # Fill in your settings

# Initialize database
flask db init
flask db migrate -m "Initial tables"
flask db upgrade

# Run application
flask run.
