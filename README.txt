Flatiron Cars Flask Routes

Overview
This project implements a small Flask app for a car company catalog.

Routes
- GET / returns: Welcome to Flatiron Cars
- GET /<model> checks the existing_models list and returns either:
  - Flatiron <model> is in our fleet!
  - No models called <model> exists in our catalog

How to run
1. Open the project folder in a terminal.
2. Run: pipenv install
3. Run: pipenv shell
4. Start the app with: python -m flask --app server.app run

How to test
Run: pipenv run pytest -q
