pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                timestamps {
                    echo 'Building..'
                }
            }
        }
        stage('Test') {
                timestamps {
                    echo 'Testing..'
                }
        }
        stage('Deploy') {
                timestamps {
                    echo 'Deploying..'
                }
        }
    }
}