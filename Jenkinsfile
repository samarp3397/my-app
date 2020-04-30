pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                 "mvn clean"
            }
        }
        stage('--test--') {
            steps {
                 "mvn test"
            }
        }
        stage('--package--') {
            steps {
                 "mvn package"
            }
        }
    }
}
