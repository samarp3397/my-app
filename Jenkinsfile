pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                 cmd 'mvn --batch-mode clean'
            }
        }
        stage('--test--') {
            steps {
                 cmd "mvn --batch-mode test"
            }
        }
        stage('--package--') {
            steps {
                cmd "mvn --batch-mode package"
            }
        }
    }
}
