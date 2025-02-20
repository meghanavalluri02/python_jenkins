pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/meghanavalluri02/python_jenkins.git'
            }
        }
        stage('Run Code') {
            steps {
                sh 'python3 script.py'  // Make sure the file name is correct and exists in your repo
            }
        }
    }
}
