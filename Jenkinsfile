pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build(job: 'N', propagate: true, quietPeriod: 1, wait: true)
      }
    }

  }
}