pipeline {
  agent any

  stages {
    stages('Hello') {
      steps {
        echo "Hello World"
      }
    }
    stages('Test'){
      steps{
        echo "This is the 2nd stage executed from SCM"
      }
    }
  }
}
