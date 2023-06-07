pipeline {
     agent any

     tools {
         // Install the Maven version configured as "MAVEN 3.9" and add it to the path.
         jdk "JAVA_HOME"
         maven "MAVEN_HOME"
     }

     stages {

         stage('Build Discovery service') {
              steps {

                 sh "mvn clean install"
                
              }
         }


     }
 }
