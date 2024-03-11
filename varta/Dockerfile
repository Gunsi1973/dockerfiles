FROM python:3
RUN apt update -y
RUN apt install iputils-ping -y
ADD main.py /
ADD requirements.txt /
RUN pip install -r requirements.txt
CMD [ "python", "./main.py" ]
