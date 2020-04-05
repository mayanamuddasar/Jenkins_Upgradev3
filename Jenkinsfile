pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        bat "Hi, this is Anshul from LevelUp360".execute()
                        bat "We are Starting the Testing"
                  }
            }
            stage('Build') {
                  steps {
                        bat "Building Sample Maven Project"execute()
                  }
            }
            stage('Deploy') {
                  steps {
                        bat "Deploying in Staging Area"execute()
                  }
            }
            stage('Deploy Production') {
                  steps {
                        bat "Deploying in Production Area"execute()
                  }
            }
      }
}