#!groovy
@Library("jenkinsLibrary@master") _
def tools = new org.devops.tools()
Hello ()
pipeline {
   agent any
   stages {
      stage('Hello') {
         steps {
               script{ 
               tools.PrintMes("获取代码","green")
               }
            }   
         }
      }
   }