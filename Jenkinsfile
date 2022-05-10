pipeline {

        agent { 
label 'slave'
 }

        stages {
            
            stage ('Bulid') {

                steps {

                     sh 'echo test'

                     sh '''

                          echo "multi line"

                          ls -lrt

                     '''
                  }
        
             }
  
         }

   }
