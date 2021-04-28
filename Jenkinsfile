pipeline {
    agent any
    stages{ 
        stage ('Checkout'){ 
        
            steps{
            echo 'Checkout'
        }
    }
     stage('Build') {
            steps {
                echo 'Clean Build'
                bat 'mvn clean compile'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Testing'
                bat 'mvn test'
            }
        }

    docker.withRegistry('https://registry.hub.docker.com', 'soumyade1999') {

        def customImage = docker.build("satymywebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
