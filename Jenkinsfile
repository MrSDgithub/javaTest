pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'master', credentialsId: 'github-credentials', url: 'https://github.com/MrSDgithub/javaTest.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                
            }
        }
    }
}
