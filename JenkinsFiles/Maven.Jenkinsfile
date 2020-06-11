#!grooxy

pipeline{
    agent { label "master"}
}
    stages{
        stage("build"){
            steps{
                script{
                    mavenhome = tool "Maven"
                    sh "${mavenhome}/bin/Maven -v"
                }
            }
        }
    }