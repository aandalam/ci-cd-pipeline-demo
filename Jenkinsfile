pipeline {
  agent any
  stages {
    stage('Archive Artifacts') {
      steps {
        archiveArtifacts(artifacts: '**/*jar', excludes: 'null')
      }
    }
  }
}