pipeline {
  agent {label "linux"}
  stages {
    stage("build") {
      steps {
        sh """
          docker build -t jenkins_test .
        """
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
