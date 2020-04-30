pipeline {
    agent any
     tools {
        maven 'Local Maven'
        jdk 'JDK'
    }
    stages {
        stage('---clean---') {
            steps {
                 sh 'mvn clean'
            }
        }
        stage('--test--') {
            steps {
                 sh "mvn test"
            }
        }
        stage('--package--') {
            steps {
                sh "mvn package"
            }
        }
    }
}
