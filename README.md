# 449-project
Group Members: Daniel Chen Wu, Jason Angel, Douglas Villalobos

# How to use
1. CLone/pull latest version of repositiory on your computer
2. Create a virtual environment and install the requirements using requirements.txt . Make your have have MySQL server and mysql_config in your PATH, otherwise you will encounter an error with mysql_config when using pip
3. Import the given 449_db database in MySQL or any other equiavlent method
4. Edit app.py to have the password to your mysql server
5. Once set up, you can run the app.py from the virtual environment and test using postman

# How to import a database
a. To import the database, open mysql and create a new connection
  
b. Once created open it and click schemas on the left. Then right click in the box labled schemas then click create schema
  
c. Once the schema is created take note of its name and the password you used to log into the connection
  
d. Next click on administration (next to schema from step a, then data import/restore.
  
e. Click import from self-contained file, and then the 3 dots on the right. Open the sql file from this repository.
  
f. Under default target schema pick the database you just made, then click start import
  
g. Relog into the connection and your database should have a new table with data that will be used for token authorization

