pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'mvn -v'
            }
        }
        stage('test'){
        	steps{
        		sh 'mvn test'
        	}
        }
        
    }
}
