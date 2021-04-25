SKIPPED STAGES IN JENKINS SCRIPTED PIPELINE


To show all stages at every build even if not executed is a 
good practice and brings transparency into pipelines 
with conditional steps or stages. Add the when condition 
to a stage of your pipeline:






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
