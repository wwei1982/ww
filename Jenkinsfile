pipeline {
  agent any
  stages {
    stage('Query Customer') {
      agent any
      environment {
        name = 'zhangsan'
      }
      steps {
        echo '1234567'
      }
    }

    stage('Query card num') {
      agent any
      steps {
        echo '%name%'
      }
    }

  }
  environment {
    name = 'wangwei'
  }
}