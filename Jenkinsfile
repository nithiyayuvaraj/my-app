pipeline {
    agent any 
    stages {
        stage('Clean') { 
            steps {
               mvn clean 
            }
        }
        stage('Test') { 
            steps {
               mvn test 
            }
        }
        stage('Deploy') { 
            steps {
                mvn package
            }
        }
    }
}
