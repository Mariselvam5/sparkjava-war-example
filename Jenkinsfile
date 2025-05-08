pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/Mariselvam5/sparkjava-war-example.git', branch: 'master'
            }
        }
        stage('Build') {
            steps {
                sh './gradlew build'
            }
        }
    }
}
