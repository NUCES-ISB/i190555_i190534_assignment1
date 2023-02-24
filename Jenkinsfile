pipeline: {   |
  agent any
           stages {
            steps {
              stage('log version info') {
                sh 'mvn --version'
                sh 'mvn clean install'
              }
            }
           }
          }
