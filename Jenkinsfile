pipeline {
    agent any
    stages {
        stage('Compile Stage') {
            steps {
            	
            	withMaven(maven:'maven'){
            			bat 'mvn --version'
            			bat 'mvn clean compile'
            	}
                
            }
        }
    }
}