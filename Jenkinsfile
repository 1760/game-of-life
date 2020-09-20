pipeline {
    agent any
    tools {
        maven "Apache Maven 3.3.9"
    }
    stages {
        stage('Build') {
            steps {
            
            sh "mvn compile"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
