pipeline{
    agent none
    options{
        buildDiscarder(logRotator(numToKeepStr:'5'))
    }
   stages{
       stage ('Remote ssh'){
           steps {
               script {

                   sh 'echo "Welcome to CI world"'

               }
           }

       }

   }
}

