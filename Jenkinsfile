pipeline {
  agent {
    label "A_119_L"
  }
  stages {
    stage('hello') {
      steps {
        sh 'sleep 5'
        sh 'echo "Hello World"'
        sh 'sleep 5'
        sh 'java -version'
        sh 'sleep 5'
        sh 'javac -version'
        sh 'sleep 5'
      }
    }
  }
}
