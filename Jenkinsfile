pipeline {
    agent any
    stages {
        stage('Install Dependencies') {
            steps {
                sh "bash install.sh" 
                sh "pip install -r requirements.txt"
                sh "pip install pytest pytest-cov"
            }
        }
        stage('Test') {
            steps {
                //
                sh "echo test here!"
            }
        }
        stage('Deploy') {
            steps {
                //
                sh "echo deployment here!"
            }
        }
    }
}
