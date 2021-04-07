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

![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/Home.jpg)

2. About 

![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/About.jpg)
4. Contact Us


![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/ContactUs.jpg)
6. Register

![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/SignUp.jpg)

![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/SignUp_Error.jpg)

![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/SignUp_Confirmation.jpg)
8. Login

![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/LogIn.jpg)
10. Dashboard

![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/LoggedInPage.jpg)
12. Stocks Page

![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/Stocks.jpg)

![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/Stocks2.jpg)
14. Stock Profile Page

![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/Stocks_Desc.jpg)
16. Predict

![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/Predict.jpg)
  * Long Term
  
![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/LongTerm.jpg)

![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/LongTerm_GOOGL.jpg)
  * Short Term
  
![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/ShortTerm.jpg)

![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/ShortTerm2.jpg)
17. Stock Analysis

![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/Analysis.jpg)
    * Long Term
    
![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/LongTermAnalysis.jpg)

![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/HistoricalRecords.jpg)
    * Short Term
    
![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/ShortTermAnalysis.jpg)
18. Compare Stocks

![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/Compare_Stocks.jpg)

![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/Stock_Comparison.jpg)

![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/Comparison_Graph.jpg)
20. NotifyMe

![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/NotifyMe.jpg)

![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/NotifyMe2.jpg)

![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/PriceChange_Alert.jpg)
22. Introduction Page

![Home Page](https://github.com/pranavshivk97/StockUp/tree/master/UI%20Images/NewToStocks.jpg)
