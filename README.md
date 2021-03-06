# cs50 2021's final-project
## About website
This is a website for a local beverage institution **Koussa**.   
It uses Flask's library   
It contains a main page, a page for registering an account, another for login, another for buying items,    
another for a bill, and the last for displaying error messages.   

## How to run the project    
This project uses Flask, which is a Python library, 
so make sure to install Python and Flask before you
try to run this project, follow the link in below to
install Python and Flask on both windows and linux   

[install python](https://www.python.org/downloads/)    

![pythondownloadcapture](https://github.com/ismailkoussa/final-project/blob/master/readme%20images/pythondownloadcapture.PNG)


[learn how to install flask](https://phoenixnap.com/kb/install-flask)   

![flaskdownloadcapture](https://github.com/ismailkoussa/final-project/blob/master/readme%20images/flaskdownloadcapture.PNG)

## About course  
This course is like a door that you open to learn programming, it's divided to 10 weeks, every week contains a lecture,    
about 2hrs, and maybe some shorts. To apply what you've learned there is 2 problems that you have to do them then    
check if they run correctly with *check50* key, then submit them using *submit50*. Week 10 contains the **final-project**     
as you see.     

## Description   
### login page   
First, when you run the code on the top you'll be directed to login page

![project-1](https://github.com/ismailkoussa/final-project/blob/master/readme%20images/project-1.PNG)     

as you see there is a form containing 2 inputs for *username* and *password*.    
make sure to enter the informations correctly, otherwise an error message will    
be displayed in a page that you'll be directed to: **apology**    

### register page    
If you don't have an account you can register one by clicking on *register* in the header as below:

![project-4](https://github.com/ismailkoussa/final-project/blob/master/readme%20images/project-4.PNG).

when you register for a new account you'll be directed to login page again.    

### index page
After you login correctly you'll be directed to index page, this is the main page of the website,
it contains a table that represents the products of the institution. 

![project-2](https://github.com/ismailkoussa/final-project/blob/master/readme%20images/project-2.PNG)

The header of this page contains two links, one for the page itself and another for a page called "buy".
lets dive into that page!   

### buy page
When you open this page you'll see a form that contains 2 inputs and 2 buttons. The first input collects   
the *product name* wich you want to buy, the second takes a number(integer) that represents the number of items.   
Next, there is a button **buy** that submits the form. You can submit it as much you want. In below of  
this button there another called *view bill* which directs you to **bill page**.

![project-3](https://github.com/ismailkoussa/final-project/blob/master/readme%20images/project-3.PNG)

### bill page
In this page the bill is displayed in a table with 3 columns:  
* **name** *name of item you've buyed*
* **Quantity** *number of items*
* **price** *price of one piece multiplyed by Quantity*   

and finally under the page the total price of package is there.

![project-5](https://github.com/ismailkoussa/final-project/blob/master/readme%20images/project-5.PNG)

### apology page  
I will not show you all the error messages, I'll let   
you know by running this project, but in the pictures  
below there is some of them    

If you enterd an unexist username     

![apology-1](https://github.com/ismailkoussa/final-project/blob/master/readme%20images/apology-1.PNG)  

If you enterd an unexist product name   

![apology-2](https://github.com/ismailkoussa/final-project/blob/master/readme%20images/apology-2.PNG)  

If you enterd an incorrect password   

![apology-3](https://github.com/ismailkoussa/final-project/blob/master/readme%20images/apology-3.PNG)
