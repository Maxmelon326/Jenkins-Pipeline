pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building the code using Maven"
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo "Running unit and integration tests using JUnit and Mockito"
            }
        }
        stage('Code Analysis') {
            steps {
                echo "Analysing the code using SonarQube"
            }
        }
        stage('Security Scan') {
            steps {
                echo "Performing security scan using OWASP Dependency-Check"
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo "Deploying the application to a staging server (AWS EC2 instance)"
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo "Running integration tests on the staging environment using Postman"
            }
        }
        stage('Deploy to Production') {
            steps {
                echo "Deploying the application to a production server (AWS EC2 instance)"
            }
        }
    }
}
