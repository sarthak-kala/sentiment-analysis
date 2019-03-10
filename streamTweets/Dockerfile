#Base-image for running python app 
FROM python:3.7-alpine

WORKDIR /home

#Copy files to image
ADD src/streamTweets.py .
ADD resources/config.ini .
ADD resources/requirements.txt .

#Install python libraries
RUN pip install -r requirements.txt
ENTRYPOINT ["./streamTweets.py"]
