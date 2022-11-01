pipeline{
agent any
  tools {
     jdk 'JAVA_HOME'
     maven 'M2_HOME'
  }
  	  environment {

        DOCKERHUB_CREDENTIALS = credentials('DockerHubID')
    }

        stages{


                 stage('Build Maven Spring'){
                             steps{
                                sh 'mvn -B -DskipTests clean install '
                             }
                         }








        }




        }

      }