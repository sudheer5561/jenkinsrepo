pipeline {

agent {

    label 'Slave1'
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


