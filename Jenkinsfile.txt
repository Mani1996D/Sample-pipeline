pipeline {
    agent any

    stages {
        stage('build 1') {
            steps {
                echo 'building application 1'
            }
        }
        stage('build 2') {
            steps {
                echo 'building application 2'
            }
        }
        stage('Test 1') {
            steps {
                echo 'Testing application 1'
            }
        }
        stage('Test 2') {
            steps {
                echo 'Testing application 2'
            }
        }
        stage('Deploy 1') {
            steps {
                echo 'Deploying application 1'
            }
        }
        stage('Deploy 2') {
            steps {
                echo 'Deploying application 2'
            }
        }
    }
}
