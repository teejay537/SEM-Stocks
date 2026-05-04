Predictive SEM Browser Model
============================

This folder gives you two ways to run the model:

OPTION 1 - EASIEST: Double-click the browser-only app
-----------------------------------------------------
Double-click:

    sem_browser_model.html

This opens the model directly in your browser. It does not require Python. It uses the same structural-equation logic in JavaScript.

OPTION 2 - Python/Streamlit app
-------------------------------
If you want the Python version, install Python first, then double-click:

    run_model_windows.bat

The first run will install the needed packages and then open the app in your browser.

Files included:
---------------
sem_browser_model.html      Browser-only clickable app
app.py                      Streamlit browser app
sem_model.py                Python SEM model class
train_model.py              Trains and saves model file
requirements.txt            Python dependencies
run_model_windows.bat       Windows launcher for the Python app
run_model_mac_linux.sh      Mac/Linux launcher

Notes:
------
The included model uses synthetic training data and demonstration equations. Replace the training data in train_model.py with your own data when you are ready to make the predictions meaningful for a real use case.
