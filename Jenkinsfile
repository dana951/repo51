pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo "This is build number $BUILD_NUMBER of demo $DEMO"
        sh """
        echo this
        echo is multi line shell step
        """
      }
    }
    stage('stage-2') {
      steps {
        echo "This is build number $BUILD_NUMBER of demo $DEMO"
        sh """
        echo this
        echo is multi line shell step
        """
      }
    }
   stage('stage-3') {
      steps {
        echo "This is build number $BUILD_NUMBER of demo $DEMO"
        sh """
        echo this
        echo is multi line shell step
        """
      }
    }
   stage('stage-4') {
      steps {
        echo "This is build number $BUILD_NUMBER of demo $DEMO"
        sh """
        echo this
        echo is multi line shell step
        """
      }
    } 

  }
  environment {
    DEMO = '1'
  }
}
