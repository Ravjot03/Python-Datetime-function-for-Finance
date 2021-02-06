# Python-Datetime-function-for-Finance

In this jupyter notebook, I have explained Python Datetime() function.

How to create and manipulate Python datetime objects to help identify key financial events.

Most problems in finance relate to changes over time. Whether we are trying to predict the future direction the market will take or analyzing the historical Cuban trade deficit.

---
## Datetime() function -

Python's Standard Library includes the datetime module which includes some useful time and date related functionality. To represent a specific time, we can use datetime objects. These objects have attributes representing the year, month, date, hour, second, microsecond, and timezone.

---
## Contents :

  - Importing `datetime` package
  - Creating a datetime object
  - Datetime from String (STRING -> DATETIME)
  
      `datetime.strptime(string, format_code)` : The strptime() class method takes two arguments.
          
          1. String (that needs to be converted)
          2. Format code
          
          Returns equivalent datetime object.
          
  - String from Datetime (DATETIME -> STRING)
  
      `datetime.strftime(format_code)` : The strftime() class method takes one or more format codes as an argument.
      
          1. Format code
          
          Returns a formatted string on the basis of format code.
