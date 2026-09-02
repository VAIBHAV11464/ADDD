pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main', url: 'https://github.com/VAIBHAV11464/ADD.git'
            }
        }
        stage('Build') {
            steps {
                bat 'python add.py'
            }
        }
    }
}
