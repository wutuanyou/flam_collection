pipeline {
  agent any
  stages {
    stage('') {
      agent any
      steps {
        sh 'newman run a.postman_collection.json -n 1 -r htmlextra,cli'
      }
    }

  }
}