pipeline {
    agent any

    tools {
        maven 'MAVEN3'
    }

    stages {
        stage('Build') {
            steps {
                
                    sh "mvn clean compile tomcat7:run" 
                
            }
        }

        // stage('Deploy') {
        //     steps {
                
        //             sh "mvn tomcat7:run"
                
        //     }
        // } 
    }
}
// pipeline {
//     agent any

//     tools {
//         maven 'MAVEN3'
//     }
    
//     stages {
//         stage('Build') {
//             steps {
//                 sh 'mvn clean compile tomcat7:run'
//             }
//         }
//     }
// }
