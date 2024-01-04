pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Build-Hello Jenkins'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Test-Hello Jenkins'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploy-Hello Jenkins'
            }
        }
    }
    
    post {
        success {
            echo 'Pipeline succeeded!'
        }
        
        failure {
            echo 'Pipeline failed!'
        }
    }
}
