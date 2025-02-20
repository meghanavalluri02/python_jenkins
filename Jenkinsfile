pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/meghanavalluri02/python_jenkins.git'
            }
        }
     
       stages {
           stage('run code'){
               steps {
                   sh 'python3 script.py'
     
       
        }
    }
}
