## StockUp: Stock Price Predictor

This repository contains the final project implemented for the Software Engineering for Web Applications graduate course at Rutgers University for Spring 2020. The project is a stock price predictor, implemented using the Django REST framework. The stock prices are predicted in the short term using polynomial curve fitting and in the long term using a neural network built from Keras.

## Run the Project
For more details on how to implement and use the server, please refer to the ServiceDocumentation.docx file. Once the Virtual environment is created and django is installed inside the environment according to the steps in the doc file, you can just copy paste all these files into the specific folders as mentioned above and run the server from the terminal.
This command can be run from the virtualstockenv/ folder which contains the manage.py file.

Command: python manage.py runserver 8100
URL for admin page: http://localhost:8100/admin
URL for landing page: http://localhost:8100

User Interface

1. Home Page (or Landing Page)

This page is the starting point of the application. Users have the option to either log in (if returning user) or register with StockUp. 

![Home Page](/UI Images/Home.png)
2. 
