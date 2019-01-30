pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'mvn clean compile'
            }
        }
        stage('Test'){
                steps{
                        sh 'mvn test'
                }
        }
        stage('package'){
                steps{
                        sh 'mvn package'
                }
        }
    }
}
