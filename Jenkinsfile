pipeline {
    agent {
        dockerfile true
    }
    
    stages {
        stage('Prueba') {
          steps {
            sh 'python3 prueba.py'
          }
        }
    }
}
