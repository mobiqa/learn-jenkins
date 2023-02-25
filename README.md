# learn-jenkins

env is used to access the variables also from outside of the script

ex: env.abc intialise with env.abc, so that abc can be accessed from outside of the script
script {
env.abc = "Hello"
def xyz = 10
def x1 = true
        }

        script {
          print "abc = ${abc}"
        }

functions:
Declare using def new1()
