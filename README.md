CPSC 449 - Web Back End Engineering
# Group Members
Daniel Chen Wu, Jason Angel, Douglas Villalobos

# How to use
1. Clone/pull latest version of repository to your computer
2. Create a virtual environment and install the requirements using requirements.txt . Make your have have mysql server and mysql_config in your PATH, otherwise you will encounter an error with mysql_config when using pip install
3. Import the given database to your mysql server
4. Edit app.py to have the password and/or name to your mysql server
5. Once set up, you can run the app.py from the virtual environment and test using postman

# How to import a database
a. To import the database, open mysql and create a new connection
  
b. Next click on administration in the left side panel, then data import/restore.
  
c. Click import from self-contained file, and then the 3 dots on the right. Open the sql file from this repository, then click start import
  
d. Relog into the connection and there will be a new schema and table with data that will be used for token authorization.

e. Use the name of that schema and the password you used to make the connection to fill the info in app.py

