FROM python:3
ENV PYTHONUNBUFFERED 1
RUN mkdir /web
WORKDIR /web
ADD . /web/
RUN pip install -r requirements.txt