pipeline {
    agent any
    stages{
        stage("complile"){
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