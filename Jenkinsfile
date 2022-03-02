pipeline {
  agent {label 'nodo_Roldan'}
  stages {
    stage('Build') {
      steps {
        sh '''
        echo 'Inicia Build'
        mvn clean install
        '''
      }
    }
    stage('Test') {
      steps {
        echo "Do something"
      }
    }
    stage('Deploy') {
      steps {
        echo "Do something"
      }
    }
  }
}
