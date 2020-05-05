FROM python:3.7.2-stretch

WORKDIR /app

ADD . /app

# instal dependencies
RUN pip3 install -r requirements.txt

# run the command to start uWSGI
CMD ["uwsgi", "app.ini"]