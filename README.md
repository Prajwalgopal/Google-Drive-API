# Google-Drive-API
Implementation of Google Drive API IN Python through Flask

Create a Python app using Flask and the Google API which will:

Support Google Authentication with Python and Flask
Restrict access via an OAuth scope, so that the app can only view and manage Google Drive files and folders which were created by the app
Read and write files on the user’s Google Drive with Python.

Prerequisites
Make sure you have the following before you start:

A Google account
The Anaconda distribution of Python

If you’re using the bash shell, create a run.sh file at your project root that looks like:

1.export FN_AUTH_REDIRECT_URI=http://localhost:8040/google/auth
2.export FN_BASE_URI=http://localhost:8040
3.export FN_CLIENT_ID=THE CLIENT ID WHICH YOU CREATED EARLIER
4.export FN_CLIENT_SECRET=THE CLIENT SECRET WHICH YOU CREATED EARLIER

5.export FLASK_APP=app.py
6.export FLASK_DEBUG=1
7.export FN_FLASK_SECRET_KEY=SOMETHING RANDOM AND SECRET

8.python -m flask run -p 8040


