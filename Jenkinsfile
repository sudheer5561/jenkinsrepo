@library('saiprisha') _
pipeline {

agent {

    label 'master'
}

stages{

    stage ('check JAVA Version') {

        steps{

           sh 'java -version'
          
        }

    }

    stage ('calling the function') {

        steps {
                welcomefun 'Sudheer'

              }
    }

    }

}


