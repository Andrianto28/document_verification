# README FOR CREDIT AI DJANGO APP

1. Start app with

   `python manage.py runserver`

   by default it runs on port 8000, but you can also specify the port by adding the port number at the end of the command, as so (for example port 8080)

   `python manage.py runserver 8080`

2. Make migrations with (APP_NAME = creditaidjango)

   `python manage.py makemigrations creditaidjango`

3. And migrate with

   `python manage.py migrate`

4. Prediction AI algorithm should go in **oracle_Vx.py**

   > dir : `"AI-DJANGO/creditaidjango/functions/oracle_Vx.py"`

5. build docker image with

   `docker build -t theophilus/djangoai:1.0 .`
