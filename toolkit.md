# Python Flask Beginner Toolkit

## 1. Title & Objective

**Technology:** Python Flask Web Framework

This toolkit demonstrates how to build a minimal web application using Flask.  
The objective is to help beginners learn how to create a simple web server that displays a "Hello World" message in the browser.

The final output is a working Flask web application that runs locally.

---

## 2. Quick Summary of the Technology

Flask is a lightweight web framework written in Python.  
It is commonly used for building web applications, REST APIs, and backend services.

It is popular because it is simple, flexible, and easy for beginners to learn.

Example real-world usage includes small web services and backend systems.

---

## 3. System Requirements

Operating System: Windows / Mac / Linux  
Programming Language: Python 3.x  
Framework: Flask  
IDE: Visual Studio Code  
Browser: Chrome, Edge, Firefox

---

## 4. Installation & Setup

Install Flask using pip:
```sh
       $pip install flask

   ```
   - Create a python file called app.py

## 5. Working example

   ```sh
      from flask import Flask

app = Flask(name)

@app.route("/")
def hello():
return "Hello, World! Welcome to my Python web app!"

if name == "main":
app.run(debug=True)
   ```
   - Run the application
    - python app.py 
        - open in browser http://127.0.0.1:5000/
            - Expected output "Hello, World! Welcome to my Python web app!"

## 6. AI Prompt Journal
   
Prompt Used:
"How do I create a simple Flask web application in Python?"

Response Summary:
The AI provided step-by-step instructions for installing Flask and creating a minimal application.

Evaluation:
The prompt helped me understand how Flask works and quickly generate working code.

## 7. Common Issues & Fixes

Error: ModuleNotFoundError: No module named 'flask'

Solution:
Install Flask using:
```sh
       $pip install flask

   ```

## 8. References

- [Flask Official Documentation](https://flask.palletsprojects.com/)
- [Python Official Documentation](https://docs.python.org/3/)
- [Real Python Flask Tutorial](https://realpython.com/flask-by-example/)
- [VS Code Python Setup Guide](https://code.visualstudio.com/docs/python/python-tutorial)
