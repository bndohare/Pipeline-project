pipeline {
    agent any
    stages{
        stage("complile"){
            void steps() {
              sh 'javac Testpipe.java'   
            }
           
        }
        stage("run"){
            steps(){
                  sh 'java Testpipe'
            }
          
        }
    }
}