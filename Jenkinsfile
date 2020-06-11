#!groovy
@Library('jenkinsLibrary') _
def tools = new org.devops.tools()
//Hello ()
pipeline {
   agent any
   stages {
      stage('Hello') {
         steps {
         
            echo 'Hello World'
               script{ 
               tools.PrintMes("获取代码","green")
               }
            }   
         }
      }
   }