pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git 'https://github.com/git/git.git'
            }
        }

        stage('Verify Files') {
            steps {
                sh 'ls -lrt'
            }
        }
    }
}
