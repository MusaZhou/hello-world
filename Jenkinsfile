pipeline {
  agent any
  stages {
    stage('Source') {
      steps {
        git 'https://github.com/MusaZhou/hello-world.git'
      }
    }

  }
  environment {
    COMPLETED_MDG = 'Build done!'
  }
}