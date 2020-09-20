pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
            
            sh "compile"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
