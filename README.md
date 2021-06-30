# Miniflix_Online_Video_Stream
The website is built with Django and SQL that allows to streams videos  for registered users.
# MINIFLIX
* A new user can register into the website by providing his/her Email ID, Username and Password.
* A user once registered can log in into the website with his/her Username/Email ID and password.
* Once logged in, Home page will be visible which displays all the movies.
* User can set the theme to light or dark.
* Movies are sorted based on Genre and production house.
* Movie description with IMDB rating is displayed for every movie.
* Any movie can be selected and streamed by the user.

# Technology Used
**Languages->** HTML, CSS, JAVASCRIPT, PYTHON

**Tools AND Frameworks->** DJANGO

**Database->** SQLITE

# HOW TO RUN
* Clone the repository and Open in Vs code
* **RUN:** pip install -r requirements.txt
* Then Run Following Commands:
    * python manage.py makemigrations
    * python manage.py migrate
    * python manage.py runserver
* To create a super user to access the django admin, run this command:
    * python manage.py createsuperuser
