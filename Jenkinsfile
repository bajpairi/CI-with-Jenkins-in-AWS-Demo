pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building from Git repo'
		mvn package
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}