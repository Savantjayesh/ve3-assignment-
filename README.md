
"# django-cicd-configuration-files" 
# CSV File Analysis Project

This project allows users to upload CSV files and process them for data analysis. The project is built using Django and includes features for user authentication, file upload, and data analysis.

## Requirements

- Python 3.12.4
- Django 5.0.7

## Installation

1. **Clone the repository:**

```bash
git clone https://github.com/1Rohitmahajan/csv_file_analysis_project.git
cd csv-file-analysis-project

python -m venv venv
venv\Scripts\activate

pip install -r requirements.txt

python manage.py migrate


python manage.py createsuperuser

python manage.py runserver
