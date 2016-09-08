FROM resin/rpi-raspbian:wheezy-2015-01-15

# Install Python.
RUN apt-get update && apt-get install -y python

RUN pip install python-telegram-bot --upgrade

COPY . /app

CMD ["python", "/app/kyrMitsos.py"]