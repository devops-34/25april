pipeline {
    agent any 
  stages {
    stage ('Test') {
      when {
                expression { env == 'None'}
            }
            steps {
                echo "Hello, Test"
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
