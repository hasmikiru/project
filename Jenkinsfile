pipeline {
    agent any

    stages {
        stage('mvn sonar:sonar -Dsonar') {
            steps {
                echo 'mvn..'
            }
        }
        stage('build') {
            steps {
                echo 'build..'
            }
        }
    }
}
