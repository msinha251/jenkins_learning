pipeline {
  agent any
  stages {
    stage("build") {
      steps {
        echo "building application"
        ehco 'test commit'
      }
    }
    
    stage("test") {
      steps {
        echo "testing application.."
      }
    }
    
    stage("deploy") {
      steps {
        echo "deploying application.."
        echo 'testing'
      }
    }
  }
}
