pipeline {
    agent any
    stages {
        stage('Compile Stage') {
            steps {
            	
            	withMaven(maven:'maven_3_5_2'){
            			bat 'mvn --version'
            	}
                
            }
        }
        
        stage('Testing Stage') {
            steps {
            	
            	withMaven(maven:'maven_3_5_2'){
            			bat 'mvn test'
            	}
                
            }
        }
        
        stage('Testing Stage') {
            steps {
            	
            	withMaven(maven:'maven_3_5_2'){
            			bat 'mvn deploy'
            	}
                
            }
        }
        
    }
}