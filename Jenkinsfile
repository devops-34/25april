pipeline {
    agent any 
  stages {
    stage ('Test') {
      when {
                expression { params.env == 'Test'}
            }
            steps {
              sh  echo "Hello, Test"
            }
    }
    stage ('UAT') {
      when {
                expression { params.env == 'UAT'}
            }
            steps {
               sh  echo "Hello, UAT"
            }
    }
   stage ('Demo') {
      when {
                expression { params.env == 'Demo'}
            }
            steps {
             sh   echo "Hello, Demo"
            }
        }
  }
}
