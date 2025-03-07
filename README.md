Use Case Generator

Project Description

Use Case Generator is a Django-based web application designed to assist software engineering teams in generating comprehensive and structured use case diagrams and descriptions for their projects. This tool helps project managers and developers by automating the creation of standard use cases based on minimal inputs. The application supports user authentication (login/signup), stores generated use cases for each user, and features a clean, user-friendly interface.
The core use case generation functionality is powered by Ivis Labs API, ensuring high-quality and accurate results.

Prerequisites

Ensure you have the following installed on your system:
	•	Python 3.8+
	•	pip (Python package manager)
	•	Virtualenv

Setup and Running the Project
	1.	Clone the Repository

git clone https://github.com/your-username/use-case-generator.git
cd use-case-generator


	2.	Initialize a Virtual Environment

python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows


	3.	Install Dependencies

pip install -r requirements.txt


	4.	Set Up Environment Variables
Create a .env file in the root directory and add your Ivis Labs API Key in the following format:

IVIS_LABS_API_KEY=YOUR_API_KEY


	5.	Apply Migrations

python manage.py makemigrations
python manage.py migrate


	6.	Run the Development Server

python manage.py runserver


	7.	Access the Application
Open your browser and go to:

http://127.0.0.1:8000/



Contributors
	•	Muskan Thakur - 4NI22CS127
	•	Naga Keerti Krith Thimmapuram - 4NI22CS129
	•	Nagashree S - 4NI22CS130
	•	Nagashreya S G - 4NI22CS131
	•	Nagaveni T R - 4NI23CS417