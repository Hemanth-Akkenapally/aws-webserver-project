# Deploying a Webserver using AWS

* EmpApp.py is a Flask Web application in Python script that facilitates adding employee details.
* It connects to MySQL database, handles the submission of employee details, inserts into the database, and uploads the images into the AWS S3 bucket.
* It includes Routing for the home page, and about page, and adding employee information.
* config.py is a file that has the details of the AWS EC2 endpoint, database instance details, S3 bucket name, and region.

# Some of the commands which we can use in the process.
sudo apt-get update
# For SQL-client
sudo apt-get install mysql-client

# For Python and related frameworks

sudo apt-get install python3\
sudo apt-get install python3-flask\
sudo apt-get install python3-pymysql\
sudo apt-get install python3-boto3

# for running the application
sudo python3 Empapp.py
