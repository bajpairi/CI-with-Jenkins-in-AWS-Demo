pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building from Git repo'
		sh 'mvn package'
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
