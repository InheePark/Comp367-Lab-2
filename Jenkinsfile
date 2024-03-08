pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script{
                    mvn clean compile 
                }
            }
        }

        stage('Deploy') {
            steps {
                script {
                    mvn tomcat7:run
                }
            }
        }
    }
}
