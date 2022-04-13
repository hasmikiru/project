pipeline {
    agent any

    stages {
        stage('mvn sonar:sonar -Dsonar') {
            steps {
                echo 'mvn..'
            }
        }
          stage("Build") {
              // Run build
              emailext subject: "Approve Build" body: "Approve build with link"
              input message: "Approve build?" submitter: "admin"
        }

          stage("Deploy") {
             // deploy artifact (only gets run after approval)
            }
        }
    }
}
