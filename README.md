# 449-project
Group Members: Daniel Chen Wu, Jason Angel, Douglas Villalobos

# How to use
1. Pull the latest version of this repository to your computer
2. Create a virtual environment and install the requirements using requirements.txt
3. If testing task 3, you will need to use the sql file to import the database int your sql server for it to work
4. Edit app.py to have the password to your mysql server and name of your database
5. Once set up, you can run the app.py from the virtual environment and test using postman

# How to import a database
a. To import the database, open mysql and create a new connection
  
b. Once created open it and click schemas on the left. Then right click in the box labled schemas then click create schema
  
c. Once the schema is created take note of its name and the password you used to log into the connection
  
d. Next click on administration, then data import/restore.
  
e. Click import from self-contained file, and then the 3 dots on the right. Open the sql file from this repository.
  
f. Under default target schema pick the database you just made, then click start import
  
g. Relog into the connection and your database should have a new table with data that will be used for token authorization

