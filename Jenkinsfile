// pipeline {
//     agent any

//     stages {
//         stage('Build') {
//             steps {
//                 withMaven {
//                     sh "mvn clean compile" 
//                 }
//             }
//         }

//         stage('Deploy') {
//             steps {
//                 withMaven {
//                     sh "mvn tomcat7:run"
//                 }
//             }
//         }
//     }
// }
pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
