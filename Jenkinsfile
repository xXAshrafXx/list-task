pipeline {
    agent any

    stages {
        stage('Checkout SCM') {
            steps {
                script {
                    checkout scm
                }
            }
        }

        stage('Run Batch Script') {
            steps {
                script {
                    bat 'script.bat' 
                }
            }
        }
    }
}
