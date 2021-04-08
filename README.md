## StockUp: Stock Price Predictor

This repository contains the final project implemented for the Software Engineering for Web Applications graduate course at Rutgers University for Spring 2020. The project is a stock price predictor, implemented using the Django REST framework. The stock prices are predicted in the short term using polynomial curve fitting and in the long term using a neural network built from Keras.

## Run the Project
For more details on how to implement and use the server, please refer to the ServiceDocumentation.docx file. Once the Virtual environment is created and django is installed inside the environment according to the steps in the doc file, you can just copy paste all these files into the specific folders as mentioned above and run the server from the terminal.
This command can be run from the virtualstockenv/ folder which contains the manage.py file.

* Command: python manage.py runserver 8100
* URL for admin page: http://localhost:8100/admin
* URL for landing page: http://localhost:8100

## User Interface

###### Home Page (or Landing Page)
This page is the starting point of the application. Users have the option to either log in (if returning user) or register with StockUp. 
![Home](/Images/Home.JPG)

###### About 
This page provides a brief description of the project.
![About](/Images/About.JPG)

###### Contact Us
This page enables usera to contact the creators of the application, i.e. my team members and I.
![Contact Us](/Images/ContactUs.JPG)

###### Register

This page helps a new user to create an account so that he/she can get started with StockUp.
![Sign Up](/Images/SignUp.JPG)

If any error occurs while filling in the fields, the user is alerted by appropriatev message.
![Sign Up Error](/Images/SignUp_Error.JPG)

Once he/she has successfully signed up, the user gets an email from the application confirming the registration.
![Registration Confirmation](/Images/SignUp_Confirmation.JPG)

###### Login
This page enables returning users to log in and access their account.
![Log In](/Images/LogIn.JPG)

###### Dashboard
Once the user is logged in, he/she can view the dashboard, which gives the 10 stock symbols along with their real-time prices.
![Dashboard](/Images/LoggedInPage.JPG)

###### Stocks Page
This page provides the user with the available stock symbols (hardcoded with the stocks listed above)
![Stocks](/Images/Stocks.JPG)
![Stocks cont.d](/Images/Stocks2.JPG)

###### Stock Profile Page
For each stock symbol listed is a profile page that provides a brief description about each stock.
![Stock Profile](/Images/Stocks_Desc.JPG)

###### Predict
This page forms the main basis of the application, the predictor module. Here, a user can choose the type of prediction, long term or short term.
![Predict](/Images/Predict.JPG)

  * Long Term
    This page predicts the corresponding stock's price over the long term, which uses the Keras neural network.
    ![Long Term](/Images/LongTerm.JPG)
    
    An example is shown below for the Google stock.
    ![Long Term](/Images/LongTerm_GOOGL.JPG)
    
  * Short Term
    This page predicts the corresponding stock's price in the short term, using the polynomial curve fitting algorithm.
    ![Short Term](/Images/ShortTerm.JPG)
    ![Short Term](/Images/ShortTerm2.JPG)
    
###### Stock Analysis
This page helps analyze the stock trends over the course of time, for the short term and the long term.
![Analysis](/Images/Analysis.JPG)

  * Long Term
    ![Long Term Analysis](/Images/LongTermAnalysis.JPG)
    ![Long Term Analysis](/Images/HistoricalRecords.JPG)
    
  * Short Term
    ![Short Term Analysis](/Images/ShortTermAnalysis.JPG)
    
###### Compare Stocks
This feature enables users to compare the trends of various stocks with the help of trends.
![Compare Stocks](/Images/Compare_Stocks.jpg)
![Compare Stocks](/Images/Stock_Comparison.JPG)
![Compare Stocks](/Images/Comparison_Graph.JPG)

###### NotifyMe
This feature enables a user to get notified if any stock that he/she keeps track of surpasses his desired price.
![Home Page](/Images/NotifyMe.JPG)
![Home Page](/Images/NotifyMe2.JPG)
![Home Page](/Images/PriceChange_Alert.JPG)

###### Introduction Page
Finally, we included a page that helps novices to familiarize themselves with the stocks
![Home Page](/Images/NewtoStocks.JPG)
