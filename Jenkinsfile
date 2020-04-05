pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo bat('Hi, this is Anshul from LevelUp360')
                        echo bat('We are Starting the Testing')
                  }
            }
            stage('Build') {
                  steps {
                        echo bat('Building Sample Maven Project')
                  }
            }
            stage('Deploy') {
                  steps {
                        echo bat("Deploying in Staging Area")
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo bat("Deploying in Production Area")
                  }
            }
      }
}