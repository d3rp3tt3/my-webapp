pipeline {
    agent any 
    stages {
        stage('build') {
            steps {
                withMaven() {
                	sh 'mvn deploy'
            	}
            }
        }
    }
}