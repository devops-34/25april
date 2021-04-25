pipeline {
    agent any 
  stages {
    stage ('Test') {
      when {
                expression { env == 'Test'}
            }
            steps {
                echo "Hello, Test1"
            }
    }
    stage ('UAT') {
      when {
                expression { env == 'UAT'}
            }
            steps {
                echo "Hello, UAT"
            }
    }
   stage ('Demo') {
      when {
                expression { env == 'Demo'}
            }
            steps {
                echo "Hello, Demo"
            }
        }
  }
}
