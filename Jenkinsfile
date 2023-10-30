pipeline {
    agent any
 
    stages {
        stage('Hello World') {
            steps {
                script {
                    sh 'python hello_world.py'
                }
            }
        }
        stage('Hello Wipro') {
            steps {
                script {
                    sh 'python hello_wipro.py'
                }
            }
        }
        stage('Hello Jenkins') {
            steps {
                script {
                    sh 'python hello_jenkins.py'
                }
            }
        }
    }
}

