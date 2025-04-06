# mlflowexperience

## How to run this project 
# First cmd conda create -p venv python==3.9 -y
# 2nd command pip install -r requirements.txt (To install all packages mention in the requirements.txt file)
# Create a file requirements.txt and app.py
# and run the app.py files
# run mlflow ui
# Problem	Solution
# 500 Errors	Likely DagsHub server issue – retry later
# 403 Forbidden	Check your API token / login credentials
# Can't log model	Avoid reusing stale or failed run IDs
# DagsHub Down	Temporarily switch to local MLflow or wait/retry