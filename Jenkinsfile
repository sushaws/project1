pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        echo 'Greetings from Jana'
      }
    }
    stage('Stage2') {
      steps {
        sh '''git checkout feature1
echo " listing Dev1 branch files"
ls -al
'''
      }
    }
    stage('finalstage') {
      steps {
        echo 'End of Pipeline'
      }
    }
  }
}
