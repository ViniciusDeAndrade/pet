�� 

pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'mvn clean compile'
            }
        }
        stage('test'){
        	steps{
        		sh 'mvn install test'
        	}
        }
        stage('deploy'){
        	steps{
        		sh 'mvn package'
        	}
        }
    }
}
