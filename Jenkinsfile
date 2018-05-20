pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh '/opt/sbt/bin/sbt-launch.jar clean'
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
