pipeline {
    agent any

    environment {
        DIRECTORY_PATH = '/var/lib/jenkins/workspace/my-project'
        TESTING_ENVIRONMENT = 'staging'
        PRODUCTION_ENVIRONMENT = 'Joseph K. Saji' 
    }

    stages {
        stage('Build') {
            steps {
                echo "Compile and package the code"
                echo "Maven (Java), npm (Node.js)"
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo "Running automated tests"
                echo "JUnit (Java), Jest (Node.js), Selenium (integration)"
            }
        }

        stage('Code Analysis') {
            steps {
                echo "Static code analysis"
                echo "SonarQube, ESLint (Node.js), Checkstyle (Java)"
            }
        }

        stage('Security Scan') {
            steps {
                echo "Vulnerability scanning"
                echo "OWASP Dependency Check, npm audit (Node.js)"
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo "Deploy to test environment"
                echo "Docker, Ansible, AWS CLI (for EC2)"
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo "Test in staging environment"
                echo "Postman, Selenium, Cypress"
            }
        }

        stage('Deploy to Production') {
            steps {
                echo "Final deployment"
                echo "Same as stage 5 with production credentials"
            }
        }
    }
}
