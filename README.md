# docker-tomcat-satylearning
A basic tutorial on running a web app on Tomcat using Docker - SATYLearning - Subscribe my youtube channel

# Steps
* Install [Docker](https://docs.docker.com/install/).
* Clone this repository - $git clone https://github.com/sathees-saty/docker-tomcat-satylearning.git
* cd docker-tomcat-satylearning # from your root directory
* $docker build -t satymywebapp .
* $docker run -p 8082:8080 satymywebapp
* http://localhost:8082
