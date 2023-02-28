@Library('roboshop') _

env.abc = "Some Data"
test1.new1()

pipeline {
 agent any
 stages {
   stage('test') {
      steps {
        script {
          env.abc = "Hello"
          def xyz = 10
          def x1 = true

         print "abc = ${abc}"
         print "xyz = ${xyz}"

          print abc



        }

        script {
          print "abc = ${abc}"
        }

      }
    }

   stage('test2') {
      steps {
        script {
          print "abc = ${abc}"
        }
      }
    }

  }

}