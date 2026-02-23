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
   
### Prompt 1:
**Prompt Used:** 
"How do I create a simple Flask web application in Python?"

**AI Response Summary:**
The AI provided step-by-step instructions for installing Flask and creating a minimal application.

**Evaluation:**
The prompt helped me understand how Flask works and quickly generate working code.

### Prompt 2
**Prompt Used:**  
"How do I install Flask using pip in Visual Studio Code?"

**AI Response Summary:**  
The AI explained how to open the terminal in VS Code and install Flask using the command pip install flask.

**Evaluation:**  
This prompt was helpful in setting up the project environment and ensuring Flask was installed correctly.

### Prompt 3
**Prompt Used:**  
"How do I create a route in Flask that displays Hello World?"

**AI Response Summary:**  
The AI explained how to use the @app.route("/") decorator to define a homepage route and return a simple text message.

**Evaluation:**  
This prompt helped me understand how routing works in Flask and how the application responds to browser requests.

### Prompt 4
**Prompt Used:**  
"How do I run a Flask application locally?"

**AI Response Summary:**  
The AI suggested running the Python file using python app.py and then accessing the application through `http://127.0.0.1:5000/` in the browser.

**Evaluation:**  
This prompt helped me test and verify that my application was working correctly.

---

### Reflection
Using AI prompts significantly improved my learning process by providing quick explanations and troubleshooting steps. It helped me understand Flask concepts faster and resolve errors efficiently during development.

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
