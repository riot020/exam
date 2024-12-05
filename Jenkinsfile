pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/your-username/system-time-script.git'
            }
        }
        stage('Run Script') {
            steps {
                sh './display-time.sh'
            }
        }
    }
}
