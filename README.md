Pitch is an app that can give different overviews.
June  29th, 2019
By Dennis  Hosea
Description
The it has number of categories.
A user can select any of the categories from the navbar to view the pitches on these categories

Other users can give feedback to the pitch posts by commenting, liking or disliking the pitch.

Specifications
Get the specs here

Set-up and Installation
Prerequiites
- Python 3.6
- Ubuntu software


Install Postgres

Create a Virtual Environment
Run the following commands in the same terminal: sudo apt-get install python3.6-venv python3.6 -m venv virtual source virtual/bin/activate

Install dependancies
Install dependancies that will create an environment for the app to run pip3 install -r requirements

Prepare environment variables
export DATABASE_URL='postgresql+psycopg2://username:password@localhost/pitchit'
export SECRET_KEY='Your secret key'
Run Database Migrations
python manage.py db init
python manage.py db migrate -m "initial migration"
python manage.py db upgrade
Running the app in development
In the same terminal type: python3 manage.py server


Technologies used
- Python 3.6
- HTML
- Bootstrap 4
- JavaScript
- Heroku for deployment
Support and contact details

License
Copyright (c) Dennis Hosea