# Geolocation_Image_Search
## Description
Geolocation Image search is build on python django and uses the flicker api for image search. You can search the images by specifying the longitude and latitude and the radius. All the images in that radius will be searched and displayed. It also provide the authentication functionality and user profile.

## How to run on local Machine
You can run the project of your local machine by follwing these steps:

1.  Install python>=3.7
2.  Download Anaconda Prompt
3.  Download PostgreSQL for database
4.  Open anaconda prompt and create a new virtual environment by command conda create -n <env_name> python= <python_version>
5.  Activate the environment you just created by command conda activate <env_name>
6.  Clone this repo by git clone
7.  Go to the project directory
8.  To install the project dependencies run command pip install -r requirements.txt
9.  Create a database in postgreSQL and set up the credentials in setting.py file according to your database.
10. Check the database changes by command py manage.py makemigrations
11. Apply the changes to the database by command py manage.py migrate
12. run the project by command py manage.py runserver

Now your project is running and you can access it at 127.0.0.1:8000
