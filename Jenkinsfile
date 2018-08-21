@Library('shared-library-sample') _

pipeline {

  agent {
    label 'non-master'
  }

  stages {
    stage('Sample Stage') {
      steps {
        listModules "$WORKSPACE/sample-pom.xml"
      }
    }
  }
}
