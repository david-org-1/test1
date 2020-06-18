pipeline {
   agent any
   stages {
      stage('Stage One') {
         steps {
            script {
               println ("tasks for stage one")
            }
         }
      }
      stage('Stage Two') {
         steps {
            script {
               println ("tasks for stage one")
            }
         }
      }
   }
   post {
      always {
         cleanWs()
      }
   }
}
