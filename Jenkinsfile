pipeline {
    agent any
    stages {
        stage('build') {
            steps {
              echo "build step"
              sleep 10
            }
        }
          stage('test') {
            steps {
                echo "test step"
            }
        }
          stage('deploy') {
            steps {
                echo 'deployement'
                sleep 10       
            }
          }
            stage('docker') {
            steps {
                echo 'image step'
            }
        }
    }
}
