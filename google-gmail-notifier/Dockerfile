FROM python:3.7

COPY requirements.txt /requirements.txt

RUN pip install -r /requirements.txt

COPY notify.py /notify.py

CMD python -u /notify.py
