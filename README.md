# AI-Blog-Generator

## cmd for postgresql database migrations

- sudo apt update
- sudo apt install python3-psycopg2
- pip3 install pytube
- sudo pip3 install pytube --break-system-packages
  By using the --break-system-packages option, you are explicitly allowing pip3 to install packages globally despite the managed environment warning.
- pip3 install assemblyai --break-system-package

- sudo service postgresql start

- python3 manage.py makemigrations
- python3 manage.py migrate

- python3 manage.py runserver
