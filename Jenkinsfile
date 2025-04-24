pipeline {
    agent any
    tools {
        maven "M3"
    }
    stages {
        stage('Build') {
            steps {
                git 'https://github.com/wonbin74/kosta-demo.git'
                sh "mvn clean package"
            }

        }
    }
}
