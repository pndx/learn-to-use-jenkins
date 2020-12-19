Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any
        stages {
            stage('Build') {
                steps {
                    echo 'Building'
                    sh './composer install'
                }
            }
            stage('Test') {
                steps {
                    echo 'Testing'
                    sh './php artisan test'
                }
            }
        }
}