# docker-tomcat-satylearning
A basic tutorial on running a web app on Tomcat using Docker - SATYLearning - Subscribe my youtube channel

# Steps
* Install [Docker](https://docs.docker.com/install/).
* Clone this repository - $git clone https://github.com/sathees-saty/docker-tomcat-satylearning.git
* cd docker-tomcat-satylearning # from your root directory
* $docker build -t satymywebapp .
* $docker run -p 8082:8080 satymywebapp
* http://localhost:8082
* windows
* Step 1:
* D:\docker-development>git clone https://github.com/sathees-saty/docker-tomcat-satylearning.git
* Step 2:
* D:\docker-development\docker-tomcat-satylearning>docker build -t satymywebapp .
* Step 3:Open docker and check the container status:
* The sampleLogin.war deployed in tomcat server
* Step 4:
* open browser
* http://localhost:8082/sampleLogin/Invoce.html
* http://localhost:8082/sampleLogin/index.jsp
* http://localhost:8082/sampleLogin/welcome.jsp
* http://localhost:8082/sampleLogin/login.jsp
* http://localhost:8082/sampleLogin/memeber.jsp

