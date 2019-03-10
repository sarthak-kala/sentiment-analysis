# sentiment-analysis
Python microservices for fetching data from twitter, filter it and analyse sentiment or mine opinion.

## Pre-requisite
Docker  (18.06.1-ce)

## Build docker images

### 1. streamTweets
To build streamTweets, run from the project home directory <br/> 
>  sudo docker build -t <img_name>:<img_tag> ./streamTweets <br/>

### 2. cleanTweets
To build cleanTweets, run from the project home directory <br/>
>  sudo docker build -t <img_name>:<img_tag> ./cleanTweets <br/>

### 3. analyseTweets
To build analyseTweets, run from the project home directory <br/>
>  sudo docker build -t <img_name>:<img_tag> ./analyseTweets <br/>

## Run docker images

### 1. streamTweets
To run streamTweets, run the docker image <br/>
>  sudo docker run -it <img_name>:<img_tag>   (for interactive mode) <br/> 
>  sudo docker run -d <img_name>:<img_tag>    (for detached mode) <br/>
  
### 2. cleanTweets
To run cleanTweets, run the docker image <br/>
>  sudo docker -it <img_name>:<img_tag>       (for interactive mode) <br/>
>  sudo docker -d <img_name>:<img_tag>        (for detached mode) <br/>

### 3. analyseTweets
To run analyseTweets, run the docker image <br/>
>  sudo docker -it <img_name>:<img_tag>       (for interactive mode) <br/>
>  sudo docker -d <img_name>:<img_tag>        (for detached mode) <br/>
