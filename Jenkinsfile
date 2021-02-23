pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is Rizwan Ahmed from Devops'
                        echo 'We are Starting the Testing'
                  }
            }
            
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area"
                  } }
                   stage('Deploy Production1') {
                  steps {
                        echo "Deploying in Production Area Marketing"
                  }
                   
            }
      }
}
