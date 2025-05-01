FROM bitnami/python:3.13

RUN apt update && apt upgrade -y

# Add dev requirements
ADD requirements.txt /tmp/
RUN pip3 install -r /tmp/requirements.txt
RUN rm /tmp/requirements.txt
