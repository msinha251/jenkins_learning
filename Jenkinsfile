pipeline {
  agent any
  stages {
    stage("build") {
      //def DOCKER_HOME = tool "docker"
      steps {
        
        echo DOCKER_HOME
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
