

---

# Property Data Analytics and Visualization Tool

## Overview
This web application empowers property owners with the ability to upload, analyze, and visualize their property data efficiently. Through a user-friendly interface, users can input data in CSV format, allowing the app to provide insightful financial metrics, including monthly returns on investment.

## Key Features
- **CSV Data Upload**: Simple and intuitive uploading of property data in CSV format.
- **Financial Calculations**: Automated calculation of monthly expenses and income for each property.
- **Data Aggregation**: Capability to compile and analyze data across all properties.
- **Data Visualization**: Dynamic visual representation of financial data through bar and pie charts.

## Technical Specifications
- **Frontend**: Crafted with HTML, Tailwind CSS, and Chart.js for an interactive user experience.
- **Backend**: Powered by Django and SQLite for robust data handling and storage.

## Installation Guide

### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Django
- SQLite
- A modern web browser (e.g., Chrome, Firefox)

### Setup Instructions

1. **Clone the Repository**
   ```
   git clone [repository-link]
   cd [repository-name]
   ```

2. **Virtual Environment Setup (Recommended)**
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**
   ```
   pip install -r requirements.txt
   ```

4. **Database Initialization**
   ```
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Launch the Application**
   ```
   python manage.py runserver
   ```
   Access the application at `http://localhost:8000`.

### How to Use
- Navigate to the CSV upload section on the web interface.
- Upload your property data file.
- Explore the automated calculations and visualizations generated by the app.

## Contributing
Your contributions are what make the community great. Suggestions and improvements are greatly appreciated. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the [MIT License](LICENSE).

---



