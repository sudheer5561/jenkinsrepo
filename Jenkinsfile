@Library('saiprisha') _
pipeline {

agent {

    label 'master'
}

stages{

    stage ('check JAVAAAAA Version') {

        steps{
           echo "checking Java Version.."
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


