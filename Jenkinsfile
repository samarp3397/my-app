pipeline {
    agent any
     tools {
        maven 'Maven 3.3.9'
        jdk 'jdk8'
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
