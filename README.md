# sentiment-analysis
Fetch data from twitter, filter it and analyse sentiment or mine opinion.

## Pre-requisite
Docker  (18.06.1-ce)

## Build docker images

### 1. streamTweets
To build streamTweets, run from the project home directory \ 
  sudo docker build -t <img_name>:<img_tag> ./streamTweets \

### 2. cleanTweets
To build cleanTweets, run from the project home directory \
  sudo docker build -t <img_name>:<img_tag> ./cleanTweets \

### 3. analyseTweets
To build analyseTweets, run from the project home directory \
  sudo docker build -t <img_name>:<img_tag> ./analyseTweets \

## Run docker images

### 1. streamTweets
To run streamTweets, run the docker image \
  sudo docker run -it <img_name>:<img_tag>   (for interactive mode) \ 
  sudo docker run -d <img_name>:<img_tag>    (for detached mode) \
  
### 2. cleanTweets
To run cleanTweets, run the docker image \
  sudo docker -it <img_name>:<img_tag>       (for interactive mode) \
  sudo docker -d <img_name>:<img_tag>        (for detached mode) \

### 3. analyseTweets
To run analyseTweets, run the docker image \
  sudo docker -it <img_name>:<img_tag>       (for interactive mode) \
  sudo docker -d <img_name>:<img_tag>        (for detached mode) 
