pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        bash 'Hi, this is Anshul from LevelUp360'
                        bash 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        bash 'Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        bash "Deploying in Staging Area"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        bash "Deploying in Production Area"
                  }
            }
      }
}