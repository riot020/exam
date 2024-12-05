pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/riot020/exam.git'
            }
        }
        stage('Run Script') {
            steps {
                sh './time.sh'
            }
        }
    }
}
















