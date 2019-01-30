pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'mvn clean install'
                sh 'mvn compile'
            }
        }
        stage('test'){
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
