pipeline {
  agent any
  stages {
    stage('DockerBuild') {
      steps {
        build(job: 'DockerBuild', wait: true)
      }
    }
  }
}