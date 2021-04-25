pipeline {
    agent any 
  stages {
    stage ('Test') {
      when {
                expression { return.env == 'Test'}
            }
            steps {
              sh  echo "Hello, Test"
            }
    }
    stage ('UAT') {
      when {
                expression { return.env == 'UAT'}
            }
            steps {
               sh  echo "Hello, UAT"
            }
    }
   stage ('Demo') {
      when {
                expression { return.env == 'Demo'}
            }
            steps {
             sh   echo "Hello, Demo"
            }
        }
  }
}
