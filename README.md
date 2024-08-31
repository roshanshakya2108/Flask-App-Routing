# Flask App Routing
This repository contains a simple Flask application demonstrating various routing methods, variable rules, form handling, and API creation.

## Introduction
This Flask application showcases different functionalities such as handling GET and POST requests, using dynamic URLs, and creating simple APIs. It is designed for beginners to understand the basics of Flask routing and request handling.

## Features
- Welcome and Index pages to demonstrate basic routing.
- Dynamic URL routing to show success or failure messages based on scores.
- A form submission example to calculate the average of three subjects and determine the pass/fail status.
- A simple API endpoint to calculate the sum of two numbers sent in a JSON request.

## Usage
To start the Flask application, run:

python app.py
The application will run on http://127.0.0.1:5000/ by default. Open this URL in your web browser to view the app.

## Endpoints
1. GET /:
Returns a welcome message.

2. GET /index:
Returns a message for the index page.

3. GET /success/int:score:
Displays a success message based on the score provided in the URL.

4. GET /fail/int:score:
Displays a failure message based on the score provided in the URL.

5. GET, POST /form:
A form page that takes three subject scores as input and calculates the average to determine pass or fail.

6. POST /api:
An API endpoint that takes two numbers in a JSON format and returns their sum.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any enhancements or bug fixes.
