pipeline {
  agent any

  stages {
    stage('Hello') {
      steps {
        echo "Hello World"
      }
    }
    stage('Test'){
      steps {
        echo "This is the 2nd stage executed from SCM"
      }
    }
    stage('Run shell script'){
      steps {
        sh '''
             chmod 755 demo.sh 
              ./demo.sh
            ''' 
      }
    }
  }
}
