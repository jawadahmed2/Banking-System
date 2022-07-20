# Banking Management System (BMS) in Flask
## Features of BMS
* Login/Register - Logout functionality
* Create/Update/Delete Customer functionality
* Create/Delete Account
* Amount Withdraw/Deposit/Transfer
* Customer/Account Status Listing page with activity
* Transaction history with excel export

## Git setup
Install [Git](https://git-scm.com/)

Go to directory you want to work on

Clone Repository : 

    https://github.com/singhnk288/Banking-Management-System-in-Flask.git

## Python Setup 

    https://www.python.org/downloads/
    
## Activate Virtual Environment [more..](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)    
    
    venv\Scripts\activate    
    
Download all dependency if any missing:

    pip install -r requirements.txt
  
Setup Mysql Server : Choose any one

    XAMP: https://www.apachefriends.org/download.html
    
    WAMP: https://www.wampserver.com/en/
    
    MySQL Community: https://dev.mysql.com/downloads/
    

Change Configuration file: 

  Go to : Banking-Management-System-in-Flask/.flaskenv and change SQLALCHEMY_DATABASE_URI path with your sql credential example:
   
  Database name: banking-system
  Username:admin
  Password:Admin@123
  
    SQLALCHEMY_DATABASE_URI='mysql://admin:Admin@123@localhost:3306/banking-system'
    
 Import Sql file:
  Go to : Banking-Management-System-in-Flask/banking-system.sql
  Import table from banking-system.sql
  
 
 ## Run Flask Project
 Inside Banking-Management-System-in-Flask directory hit
 
    flask run
    

    
    


    
