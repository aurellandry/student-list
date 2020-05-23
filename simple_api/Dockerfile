FROM python:latest
ADD . /api
WORKDIR /api
RUN apt-get update && apt-get install -y libsasl2-dev python-dev libldap2-dev libssl-dev
RUN apt-get install -y python-ldap
RUN pip install --upgrade pip
RUN pip install flask
RUN pip install flask-httpauth flask-simpleldap

