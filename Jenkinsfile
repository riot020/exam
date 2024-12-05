pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/riot020/exam.git'
            }
        }
        stage('Run Script') {
            steps {
                sh './time.sh'
            }
        }
    }
}
