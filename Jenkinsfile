pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the project using Maven'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Running tests using JUnit and Postman/Newman'
            }
        }
        stage('Code Analysis') {
            steps {
                echo 'Analyzing code using SonarQube'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Scanning for vulnerabilities using OWASP Dependency-Check'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Deploying to staging server on AWS EC2'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Running integration tests '
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Deploying to production server on AWS EC2'
            }
        }
    }
}
