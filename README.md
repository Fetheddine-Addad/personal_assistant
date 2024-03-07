## Chatbot Task Planner with Django and Gemini

**Introduction**

This project creates a chatbot task planner using Django for the web framework and Google Gemini for natural language processing.

**Requirements**

* Python 3.x (refer to documentation for installation)
* Django (`pip install django`)
* Google Generative AI Client Library (`pip install google-generativeai`)
* Python-dotenv (`pip install python-dotenv`)

**Setup**

Create .env File:

create a file named .env in the project's root directory.

Add the following line, replacing <your_gemini_api_key> with your actual Gemini API key obtained from Google Cloud Console:

GEMINI_API_KEY=<your_gemini_api_key>

### Create Superuser:
python manage.py createsuperuser

### run
python manage.py runserver 

login using the credentials you've created 
