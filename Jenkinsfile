pipeline {
  agent any
  stages {
    stage("build") {
      steps {
        echo "building application"
        echo 'test commit'
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
