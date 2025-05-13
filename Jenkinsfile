pipeline {
    agent any
    tools {
        jdk 'JDK17'
        maven 'maven'
    }
    stages {
        stage('Build') {
            steps {
                sh 'java -version'
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}