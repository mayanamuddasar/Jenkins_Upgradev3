pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        println "Hi, this is Anshul from LevelUp360".execute()
                        bat "We are Starting the Testing"
                  }
            }
            stage('Build') {
                  steps {
                        println "Building Sample Maven Project"execute()
                  }
            }
            stage('Deploy') {
                  steps {
                        println "Deploying in Staging Area"execute()
                  }
            }
            stage('Deploy Production') {
                  steps {
                        println "Deploying in Production Area"execute()
                  }
            }
      }
}