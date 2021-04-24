pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'deploying'
            }
        }
        stage('Test') {
            when {
                branch 'Test'
                environment name: 'env', value: 'Test'
            }
            steps {
                echo 'Test'
            }
        }
        
        
         stage('UAT') {
            when {
                branch 'Test'
                environment name: 'env', value: 'UAT'
            }
            steps {
                echo 'UAT'
            }
        }
    }
}
