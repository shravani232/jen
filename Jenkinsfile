pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/shravani232/jen.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the website...'
            }
        }
    }
}
