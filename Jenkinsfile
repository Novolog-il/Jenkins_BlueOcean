pipeline {
  agent any
  stages {
    stage('Hello') {
      parallel {
        stage('Hello') {
          steps {
            echo 'Hello World'
          }
        }

        stage('AA1') {
          steps {
            mail(subject: 'aa', body: 'aaaaaa', from: 'avrahama@novolog.co.ol', to: 'avrahama@novolog.co.ol')
          }
        }

      }
    }

  }
}