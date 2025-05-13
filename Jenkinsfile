pipeline {
    agent any
    tools {
        jdk 'JDK8'
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