#！groovy
@Library('jenkins-devops')_
def tools = new org.devops.tools()
pipeline {
   agent any
   stages {
      stage('Hello') {
         steps {
            echo 'Hello World'
            tools.PrintMes（'this is my pipeline'）
         }
      }
   }
}