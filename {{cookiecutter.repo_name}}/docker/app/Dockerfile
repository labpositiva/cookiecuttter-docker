FROM python:3.6.1

MAINTAINER {{cookiecutter.full_name}} {{cookiecutter.email}}

COPY ./requirements/ /usr/src/requirements/
COPY ./requirements.txt /usr/src/requirements.txt

# set working directory to /usr/src/
WORKDIR /usr/src/

# install python dependencies
RUN pip install -r /usr/src/requirements.txt
