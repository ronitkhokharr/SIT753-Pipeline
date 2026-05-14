pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Stage 1: Build'
                echo 'Task: Compiling and packaging source code using Maven build automation tool.'
                echo 'Tool: Maven'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Stage 2: Unit and Integration Tests'
                echo 'Task: Running unit tests with JUnit and integration tests with Selenium.'
                echo 'Tools: JUnit (unit tests), Selenium (integration tests)'
            }
        }
        stage('Code Analysis') {
            steps {  
                echo 'Stage 3: Code Analysis'
                echo 'Task: Analysing code quality and standards using SonarQube.'
                echo 'Tool: SonarQube'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Stage 4: Security Scan'
                echo 'Task: Scanning dependencies for vulnerabilities using OWASP Dependency-Check.'
                echo 'Tool: OWASP Dependency-Check'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Stage 5: Deploy to Staging'
                echo 'Task: Deploying application to AWS EC2 staging instance.'
                echo 'Tool: AWS CLI / AWS CodeDeploy'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Stage 6: Integration Tests on Staging'
                echo 'Task: Running integration tests on staging environment using Selenium.'
                echo 'Tool: Selenium / Postman'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Stage 7: Deploy to Production'
                echo 'Task: Deploying verified build to AWS EC2 production instance.'
                echo 'Tool: AWS CLI / AWS CodeDeploy'
            }
        }
    }
}
