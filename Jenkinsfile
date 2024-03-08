// pipeline {
//     agent any
//
//     tools {
//         maven 'MAVEN3'
//     }
//
//     stages {
//         stage('Build') {
//             steps {
//                 sh 'mvn clean package'
//             }
//         }
//     }
// }
pipeline {
    agent any

    tools {
        maven 'MAVEN3'
    }

    stages {
        stage('Build') {
            steps {
                sh "mvn clean package"
            }
        }

        stage('Deploy') {
            steps {
                sh "mvn tomcat7:deploy"
            }
        }
    }
}
