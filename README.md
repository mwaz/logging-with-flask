# Flask Application Logging

---
- Flask program for setting Logging and logging configuration.
<p>This application records logs as the application is running and outputs them to `warnings.log`
  
  
### Content
- App covers all the logging levels of the Python Logging module.
  ** levels covered: 
  | Level | Severity|
  |---|---|
  |1. Debug| 10|
  |2. Info | 20|
  |3. Warning | 30 |
  |4. Error | 40|
  |5. Critical | 50|
  

## Setup & Running
- Clone repo `https://github.com/Willbeckh/flask-app-logging.git`
- Open IDE & `cd logging-with-flask`
- create a `.env` file, and add environment variables 
- such as; 
   - `FLASK_APP=app.py`
- To run the app. Type, `flask run`

## Tests
Included unittests for testing Logging configuration.
- Running the tests `python -m test_app.py`
