pipeline
{
     agent any
      tools {
           maven 'maven'
           }
      stages {
             stage ( 'compile' ) {
                    scripts {
                            sh 'mvn compile'
                     }
              }
              stage( 'test' ) {
                     steps {
                             sh 'mvn test'
                      }
               }
               stage( 'package' ) {
                       steps {
                               sh 'mvn package'
                        }
                }
         }
}      
