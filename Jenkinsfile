pipeline {
    agent any

    stages {
        stage('pullJob') {
            steps {
                echo 'Building..'
            }
        }
        stage('buildJob') {
            steps {
                echo 'Testing..'
            }
        }
        stage('testJob') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}