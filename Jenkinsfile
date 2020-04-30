pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                 bat 'mvn --batch-mode clean'
            }
        }
        stage('--test--') {
            steps {
                 bat "mvn --batch-mode test"
            }
        }
        stage('--package--') {
            steps {
                bat "mvn --batch-mode package"
            }
        }
    }
}
