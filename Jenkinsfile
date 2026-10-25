pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/ky0i/Midterm-Assignment.git'
            }
        }
        stage('Build Fat Jar') {
            steps {
                sh './mvnw clean package'
            }
        }
    }
}
