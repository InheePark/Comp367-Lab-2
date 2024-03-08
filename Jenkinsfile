pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                mvn clean compile 
            }
        }

        stage('Deploy') {
            steps {
                mvn tomcat7:run
            }
        }
    }
}
