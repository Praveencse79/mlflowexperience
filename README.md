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
# https://dagshub.com/Praveencse79/mlflowpractice.mlflow
# Endpoint URL: # https://dagshub.com/api/v1/repo-buckets/s3/Praveencse79 
# Public Key ID and Secret Access Key: 721322a1417c068480c604b1c1480bc5a9094320
# $ export https://dagshub.com/Praveencse79/mlflowpractice.mlflow
bash: export: `https://dagshub.com/Praveencse79/mlflowpractice.mlflow': not a valid identifier

prave@DESKTOP-6NEVEKQ MINGW64 /d/MLFLOW & DAGSHUB/mlflowexperience (main)
$ export MLFLOW_TRACKING_URI=https://dagshub.com/Praveencse79/mlflowpractice.mlflow

prave@DESKTOP-6NEVEKQ MINGW64 /d/MLFLOW & DAGSHUB/mlflowexperience (main)
$ export MLFLOW_TRACKING_USERNAME=Praveencse79

prave@DESKTOP-6NEVEKQ MINGW64 /d/MLFLOW & DAGSHUB/mlflowexperience (main)
$ export MLFLOW_TRACKING_PASSWORD=721322a1417c068480c604b1c1480bc5a9094320

prave@DESKTOP-6NEVEKQ MINGW64 /d/MLFLOW & DAGSHUB/mlflowexperience (main)

How to create mlruns? When we run the app.py file.