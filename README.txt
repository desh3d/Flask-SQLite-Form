
cd C:\Users\dhira\Desktop\mywork\Working Projects\FlaskQuotesForm--- This folder should contain main.py file and helloapp folder
# helloapp folder contains all the project files




# PROJECT is simple Flask Integration with SQLite database
#Wher users can store and acces famous quotes by various people.

# before running project Create above directory and verify files. Also create a virtual env if possible to run in different computer


# TO Run -- type following commands in cmd

cd C:\Users\dhira\Desktop\mywork\Working Projects\FlaskQuotesForm

set FLASK_APP=main    # this exports flas app to cmd so that we can run main.py file

flask run    ----- This runs the project


# it contains 
1) an sql lite database file named hello.db which store a response quote from url (http://127.0.0.1:5000/addquote/)
2) it contains html template for various urls that display respective site
	1)http://127.0.0.1:5000/quotes/ ---  this will display all quotes in database
	2)http://127.0.0.1:5000/addquote/  --- this is to add a quote in database and will redirect to below url, when submit is pressed
	3)http://127.0.0.1:5000/addquote/ --- This gives two link, Home and List of all quotes w
	4)http://127.0.0.1:5000/hello/David/ --- Here david can be any name, it will display your name and any 1 of random quote for the day
	5)http://127.0.0.1:5000/    --- This will simply display a hello message

# For Now the html files have no CSS or any complex structure but they have a database connected to them soit can accept data and 
# STORE DATA  and DO ANYTHING WITH that data.


# Project can be modified as per desire and aplication.