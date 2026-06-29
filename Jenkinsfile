pipeline {

    agent any

    stages {

        stage('Checkout Code') {

            steps {

                git branch: 'main',
                    url: 'https://github.com/ashapatilgithub/flask-devops-app_v2.git'

            }

        }

        stage('List Files') {

            steps {

                sh 'ls -la'

            }

        }

    }

}