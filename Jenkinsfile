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
        sh '''git branch -a
echo " Listing branches & files"
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
