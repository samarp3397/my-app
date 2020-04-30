pipeline {
    agent any
     tools {
        maven 'Local Maven'
        jdk 'JDK'
    }
    stages {
        stage('---clean---') {
            steps {
                 bat " call mvn clean"
            }
        }
        stage('--test--') {
            steps {
                 bat " call mvn test"
            }
        }
        stage('--package--') {
            steps {
                bat "call mvn package"
            }
        }
    }
}
