pipeline {
    agent any
    stages{
        stage("build"){
            steps() {
              sh 'javac Testpipe.java'   
            }
           
        }
        stage("run"){
            steps(){
                  sh 'java Testpipe'
            }
          
        }
    }
    post{
        always
        sh 'good work'
    }
}