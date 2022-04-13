pipeline {
    agent any

    stages {
        stage('mvn sonar:sonar -Dsonar') {
            steps {
                echo 'mvn sonar..'
            }
        }
        stage('Hello world') {
            steps {
                echo 'hello world..'
        }
    }
}
