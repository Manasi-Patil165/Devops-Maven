pipeline {
    agent any

    tools {
        maven 'Maven'
    }

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Manasi-Patil165/DevOps-Maven.git'
            }
        }

        stage('Build') {
            steps {
                bat 'mvn clean install'
            }
        }
    }
}
