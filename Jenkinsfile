pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'mvn -v'#'mvn clean install package -DskipTests'
            }
        }
        stage('test'){
        	steps{
        		sh 'mvn test'
        	}
        }
        
    }
}
